pipeline {
    agent {
	docker
    }
    stages {
        stage('Test') {
            steps {
                sh './test.sh'
            }
        }
    }
}