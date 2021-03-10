pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('Python version') {
            steps {
                sh 'python --version'
            }
        }
        stage('PHP version') {
            agent { docker { image 'php' } }
            steps {
                sh 'php --version'
            }
        }
    }
}
