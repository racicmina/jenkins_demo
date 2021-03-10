pipeline {
    agent { docker { image 'php' } }
    stages {
        stage('PHP version 2') {
            steps {
                sh 'php --version'
            }
        }
    }
}
