pipeline {
    agent any
    tools {
        go 'go-1.11'
    }
    environment {
        GO111MODULE = 'on'
    }
    def userInput = input(
 id: 'userInput', message: 'continue', parameters: [
 [$class: 'TextParameterDefinition', defaultValue: '4/qQHR5YnYsCNphGK2FsDw3egv5UglI_ssIL86EtfYzFBP9W0Dm6eOsK8', description: 'Environment', name: 'env']
])
    stages {
        stage('version'){
          steps{
            sh ' go version'
            sh 'which go'
            sh 'git version'
            sh 'claat export hello.md'
            sh 'echo userInput'
            sh 'echo $userInput'
          }
        }
    }
}

