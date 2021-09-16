pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                bat 'docker build -t docker_start .'
                
            }
        }
    }
}