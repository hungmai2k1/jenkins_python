pipeline {
  agent any
  environment {
    Path = "C:\\Windows\\System32;C:\\Users\\hung.mai-xuan\\AppData\\Local\\Microsoft\\WindowsApps\\Microsoft.DesktopAppInstaller_8wekyb3d8bbwe"
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
