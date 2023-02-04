pipeline {
  agent any
  stages {
    stage('prepare needed tools') {
      steps {
        sh 'pip install autopep8 pylint pytest'
      }
    }

  }
}