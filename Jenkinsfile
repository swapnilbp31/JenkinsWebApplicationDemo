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
        bat '"\\usr\\lib64\\dotnet\\sdk\\8.0.112\\MSBuild.dll" "C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\TestPipeline\\JenkinsWebApplicationDemo.sln" /p:Configuration=Release'
    }
}
        
}