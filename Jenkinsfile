pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Megha-Knight/myproject.git'
            }
        }

        stage('Build') {
            steps {
                bat 'python app.py'
            }
        }
    }
}