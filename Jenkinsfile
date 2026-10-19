pipeline {
    agent any

 

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/YoriStark/jenkinsTest.git'
            }
        }
        stage('Date') {
            steps {
                sh 'date'
            }
        }
    }
}