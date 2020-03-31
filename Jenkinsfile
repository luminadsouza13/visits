pipeline {
  agent any
  stages {
    stage('Docker build') {
      steps {
        docker-compose up --build
      }
    }

  }
}
