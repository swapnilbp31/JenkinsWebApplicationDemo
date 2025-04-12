pipeline {
    agent any
    environment {
        dotnet = 'C:\\Program Files\\dotnet\\dotnet.exe'
    }
    stages {
        stage('Checkout Stage') {
            steps {
                git credentialsId: '5ba5e0da-116a-47df-8e8c-639f4654358c', url: 'https://github.com/Jaydeep-007/JenkinsWebApplicationDemo.git', branch: 'main'
            }
        }
    }
}