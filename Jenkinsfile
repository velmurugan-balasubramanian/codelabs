pipeline {
    agent any
    tools {
        go 'go-1.11'
    }
    environment {
        GO111MODULE = 'on'
    }
    stages {
        stage('version'){
          steps{
            sh ' go version'
            sh 'go get github.com/googlecodelabs/tools/claat'
            sh 'claat export hello.md'
          }
        }
    }
}