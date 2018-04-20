pipeline {
  agent any
  stages {
    stage('join the dir') {
      steps {
        sh 'cd ../hello_world'
      }
    }
    stage('gcc') {
      steps {
        sh 'gcc hello_world.c -o hello'
      }
    }
    stage('run ') {
      steps {
        sh './hello'
      }
    }
    stage('print') {
      steps {
        echo 'success'
      }
    }
  }
}