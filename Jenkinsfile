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
    }
}