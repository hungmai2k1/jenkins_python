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
          bat 'python --version'
        }
      }
    }
    stage('hello') {
      steps {
        script {
          echo 'test1'
          bat 'python python.py'
        }
      }
    }
  }
}
