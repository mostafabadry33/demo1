pipeline {
    agent any

    stages {
        stage('scm checkout') {
            steps {
              git 'https://github.com/mostafabadry33/demo1.git'
              
                echo 'checkout complate..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
