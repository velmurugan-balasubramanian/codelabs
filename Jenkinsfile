pipeline {
    agent { docker { image 'golang' } }
    stages {
        stage('build') {
            steps {
                sh 'echo works'
                sh 'go version'
            }
        }
    }
}