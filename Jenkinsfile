pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/mostafabadry33/demo1.git'
                echo 'checkout compalte..'
            }
        }
           
        stage('Build') {
            steps {
                echo 'Building..'
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

