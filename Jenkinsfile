pipeline {
  agent any
  stages {
    stage('setup') {
      steps {
        sh 'pip install autopep8 pylint pytest'
      }
    }

    stage('build') {
      steps {
        sh 'echo \'hello\''
      }
    }

  }
}