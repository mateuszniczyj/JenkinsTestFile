pipeline {
    agent {
        docker { image 'node:14-alpine' }
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
  //agent any
  //stages {
    //stage("build") {
      //steps {
        //bat """
          //docker build -t hello_there .
        //"""
      //}
    //}
    //stage("run") {
      //steps {
        //sh """
          //docker run --rm hello_there
        //"""
      //}
    //}
  //}
//}




//pipeline {
  //agent any
  //stages {
    //stage("build") {
      //steps {
        //script {
		//dockerFingerprintFrom dockerfile: 'Dockerfile', image: 'docker_start'
		//sh 'docker build -t docker_start .'
		//}
      //}
    //}
    //stage("run") {
    //  steps {
    //    sh """
    //      docker run --rm docker_start
    //    """
    //  }
    //}
  //}
//}