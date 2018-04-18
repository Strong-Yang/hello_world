pipeline {
  agent any
  stages {
    stage('join in the dir') {
      steps {
        sh '''pushed /home/wlh/hello_world
'''
      }
    }
    stage('gcc') {
      steps {
        sh 'make'
      }
    }
    stage('run') {
      steps {
        sh './hello'
      }
    }
    stage('end') {
      steps {
        echo 'test end'
      }
    }
  }
}