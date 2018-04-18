pipeline {
  agent any
  stages {
    stage('join in the dir') {
      steps {
        sh '''/home/wlh/hello_world
'''
      }
    }
    stage('gcc') {
      steps {
        sh 'gcc hello_world.c -o hello_world'
      }
    }
    stage('run') {
      steps {
        sh './hello_world'
      }
    }
    stage('end') {
      steps {
        echo 'test end'
      }
    }
  }
}