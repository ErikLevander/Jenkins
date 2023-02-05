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
        sh 'python3 -m autopep8 --diff ./src/main.py'
      }
    }

  }
}