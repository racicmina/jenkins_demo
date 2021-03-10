pipeline {
    agent { docker { image 'php' } }
    stages {
        stage('PHP version') {
            steps {
                sh 'php --version'
            }
        }
    }
}
