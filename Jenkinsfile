pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'docker build -t app'
      }
    }
    stage('test') {
      steps {
        echo 'TEST'
      }
    }
    stage('Deploy') {
      steps {
        echo 'DEPLOY'
      }
    }
  }
}