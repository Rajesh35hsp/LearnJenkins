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
                bat "\"C:/Program Files/dotnet/dotnet.exe\" build \"${workspace}/SampleApp\""
            }
        }
    }
}