pipeline {
  agent any
  stages {
    stage('prepare needed tools') {
      steps {
        sh 'pip3 install autopep8 pylint pytest'
      }
    }

  }
}