pipeline {
    agent { dockerfile true }
    stages {
        stage('Build Stage'){
            steps {
                sh "docker-compose up -d"
            }
        }
    }
}