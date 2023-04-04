pipeline {
  agent any
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
