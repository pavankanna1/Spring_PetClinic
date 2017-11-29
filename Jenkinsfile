pipeline {
    agent {
    node {
      label 'Ansible-Agent'
    }
	}
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}