pipeline {
  agent any
  stages {
    stage('sleep') {
      steps {
        sleep 3
        dir(path: 'cn_pilot_project\\src\\web') {
          sh 'docker build -t cn_pilot_web .'
        }

      }
    }
  }
}