pipeline {
  agent {
    docker { image 'node:16-alpine' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
      }
    }
  }
}







//pipeline {
//    agent { dockerfile true }
//    stages {
//        stage('Test') {
//            steps {
//                bat 'docker build -t docker_start .'
//                
//            }
//        }
//    }
//}