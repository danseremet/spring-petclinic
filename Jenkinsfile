pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh './mvnw package'
      }
    }

    stage('Test') {
      steps {
        sh './mvnw test'
      }
    }

    stage('Deploy') {
      steps {
        sh './mvnw deploy'
      }
    }

  }
}