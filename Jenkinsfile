pipeline {
  agent any
  environment {
    Path = "C:\\Windows\\System32"
  }
  stages {
    stage('version') {
      steps {
        bat 'cmd python --version'
      }
    }
    stage('hello') {
      steps {
        bat 'cmd python python.py'
      }
    }
  }
}
