pipeline {
  agent any
  environment {
    Path = "C:\\Windows\\System32"
  }
  stages {
    stage('version') {
      steps {
        bat 'python --version'
      }
    }
    stage('hello') {
      steps {
        bat 'python python.py'
      }
    }
  }
}
