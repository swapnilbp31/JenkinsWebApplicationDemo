pipeline {
    agent any
    environment {
        dotnet = 'C:\\Program Files\\dotnet\\dotnet.exe'
    }
    stages {
        stage('Checkout Stage') {
            steps {
               git url: 'https://github.com/swapnilbp31/JenkinsWebApplicationDemo.git', branch: 'main'
            }
        }
    }
      stage('Build Stage') {
            steps {
                bat 'C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\TestPipeline\\JenkinsWebApplicationDemo.sln --configuration Release'
            }
        }
}