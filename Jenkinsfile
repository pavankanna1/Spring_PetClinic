pipeline {
    agent {
    node {
      label 'Ansible-Agent'
    }
	}
    stages {
        stage('build') {
            steps {
			    sh 'yum install git -y'
                sh 'mvn --version'
            }
        }
    }
}