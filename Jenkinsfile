
pipeline {
    agent any
    tools {
        go 'go'
    }
    environment {
        GOMODULE = 'on'
    }

    stages {
        stage('Compile') {
            steps {
                sh 'go version'
            }
        }

}