pipeline {
    agent {
    node {
      label 'Ansible-Agent'
    }
	}
    stages {
        stage('build') {
            steps {
			    sh '/opt/apache-maven-3.5.2/bin/mvn clean install' 
            }
        }
    }
}