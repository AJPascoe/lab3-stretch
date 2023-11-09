pipeline {
    agent any
    stages {
        stage('Build Stage'){
            steps {
                sh "sudo apt update \
                    sudo apt install -y curl \
                    curl https://get.docker.com | sudo bash \
                    sudo usermod -aG docker $Jenkins"
                sh "docker build -t nginx"
            }
        }
    }
}