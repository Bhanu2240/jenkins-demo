pipeline {

    agent any

    stages {

        stage('Build') {
            steps {
                bat 'echo Building from Multi-Branch Pipeline'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Running Tests'
            }
        }
    }

    post {

        success {
            bat 'echo Multi-Branch Pipeline Success'
        }
    }
}
