pipeline {
  agent any
  environment {
    Path = "C:\\Windows\\System32"
  }
  stages {
    stage('version') {
      steps {
        script {
          bat 'python --version'
        }
      }
    }
    stage('hello') {
      steps {
        script {
          bat 'python python.py'
        }
      }
    }
  }
}
