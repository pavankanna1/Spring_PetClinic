pipeline {
    agent {
    node {
      label 'Ansible-Agent'
    }
	}
	def yum = { packages ->
    ["sudo yum install -y zip unzip telnet"] }
	
    stages {
        stage('build') {
            steps {
			    sh '/opt/apache-maven-3.5.2/bin/mvn clean install' 
            }
        }
    }
}