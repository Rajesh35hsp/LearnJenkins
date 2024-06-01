pipeline{
    agent any
    stages{
        stage ('Clean workspace') {
            steps {
                cleanWs()
                  }
                }

        stage("build stage"){
            
            steps{
                sh "/usr/local/bin/dotnet build \"${workspace}/SampleApp\""
            }
        }
    }
}