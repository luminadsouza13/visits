pipeline {
  agent docker
  stages {
    stage('Docker build') {
      steps {
        docker-compose up --build
      }
    }

  }
}
