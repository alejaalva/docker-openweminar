pipeline {
  agent any
  stages {
    stage('inicio') {
      steps {
        echo 'Hola desde estage 1'
      }
    }
    stage('test2') {
      agent any
      steps {
        echo 'Hola desde estage2'
      }
    }
  }
}