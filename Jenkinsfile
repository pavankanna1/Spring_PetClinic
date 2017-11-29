pipeline {
    agent {
    node {
      label 'Ansible-Agent'
    }
	}
    stages {
        stage('build') {
            steps {
			    yum install git -y
                sh 'mvn --version'
            }
        }
    }
}