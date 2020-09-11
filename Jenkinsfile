pipeline {
  agent any
  stages {
    stage('Lint HTML') {
      steps {
        sh 'tidy -q -e --drop-empty-elements no ./web/*.html'
      }
    }

  }
}