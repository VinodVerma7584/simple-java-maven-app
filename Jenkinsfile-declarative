pipeline {
    agent any
    
    stages {
        stage('checkout') {
            steps {
                echo 'Checkout..'
                checkout scm
            }
        }

    stages {
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
