pipeline {
  agent any
  stages {
    stage('setup') {
      steps {
        sh 'pip install autopep8 pylint pytest'
      }
    }

    stage('Code quality') {
      steps {
        sh 'touch 1.txt'
      }
    }

  }
}