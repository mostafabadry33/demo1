pipeline {
  agent any
  stages {
    stage('checkout') {
      parallel {
        stage('checkout demo 1') {
          steps {
            echo 'checkout compalte'
          }
        }

        stage('checkout demo2') {
          steps {
            echo 'compalte'
          }
        }

      }
    }

  }
}