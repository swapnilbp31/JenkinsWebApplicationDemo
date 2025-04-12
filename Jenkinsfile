pipeline {
    agent any
    environment {
        dotnet = 'C:\\Program Files\\dotnet\\dotnet.exe'
    }
    stages {
        stage('Checkout Stage') {
            steps {
                git  'https://github.com/swapnilbp31/JenkinsWebApplicationDemo.git', branch: 'main'
            }
        }
    }
}