pipeline {
    agent any 
    stages {
        stage('Verify tooling') {
            steps {
                sh '''
                docker version
                docker info
                '''
            }
        }

        stage('Start container') {
            steps {
	    	sh 'docker compose up -d'
	    	sh 'docker ps'
            }
        }
    }
}