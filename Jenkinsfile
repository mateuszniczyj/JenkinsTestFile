pipeline {
  agent {dockerfile true}
  stages {
    stage("build") {
      steps {
        sh """
          docker build -t hello_there .
        """
      }
    }
    stage("run") {
      steps {
        sh """
          docker run --rm hello_there
        """
      }
    }
  }
}




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