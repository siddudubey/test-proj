pipeline {
  agent any
  stages {
    stage('Say Hello') {
      parallel {
        stage('Say Hello') {
          steps {
            sh 'echo HELLO'
          }
        }

        stage('Say GOOD') {
          steps {
            sh 'echo GOOD to See you!'
          }
        }

      }
    }

    stage('DONE') {
      steps {
        echo 'DONE!'
      }
    }

  }
}