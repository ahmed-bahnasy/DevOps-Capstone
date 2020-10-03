pipeline {
  agent any
  stages {
    stage('Lint python') {
      steps {
        sh 'tidy -q -e --drop-empty-elements no ./*.py'
      }
    }

  }
}
