pipeline {
  agent any
  stages {
    stage('staging') {
      steps {
        sh 'docker build -t test_jenkins .'
      }
    }
  }
}