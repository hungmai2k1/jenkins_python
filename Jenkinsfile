pipeline {
  agent any
  environment {
    Path = "C:\\Windows\\System32"
  }
  stages {
    stage('version') {
      steps {
        script {
          echo 'test'
          bat 'py --version'
        }
      }
    }
    stage('hello') {
      steps {
        script {
          echo 'test1'
          bat 'py test.py'
        }
      }
    }
  }
}
