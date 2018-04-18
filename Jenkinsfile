pipeline {
  agent any
  stages {
    stage('gcc') {
      steps {
        sh 'gcc hello_world -o hello_world'
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