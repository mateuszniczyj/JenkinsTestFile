pipeline {
  agent {dockerfile true}
  stages {
    stage("build") {
      steps {
        script {
		sh 'docker build -t docker_start .'
		}
      }
    }
    //stage("run") {
    //  steps {
    //    sh """
    //      docker run --rm docker_start
    //    """
    //  }
    //}
  }
}