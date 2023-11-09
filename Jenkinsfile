pipeline {
    agent any
    stages {
        stage('Build Stage'){
            steps {
                sh "chmod +x buildstage.sh"
                sh "docker compose up -d"
            }
    }
}
