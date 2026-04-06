pipeline {
    agent any

    environment {
        PATH = "C:\\Users\\arun\\AppData\\Local\\Programs\\Python\\Python312;${env.PATH}"
    }

    stages {
        stage('Build') {
            steps {
                bat 'python app.py'
            }
        }
    }
}
