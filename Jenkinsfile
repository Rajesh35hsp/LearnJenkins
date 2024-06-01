pipeline{
    agent any
    stages{
        stage("build stage"){
            
            steps{
                echo "this is stage 1"
                sh "dotnet build"
            }
        }
        
        stage("stage 2"){
            steps{
            echo "this is stage 2"
            }
        }
        
        stage("stage 3"){
            steps{
            echo "this is stage 3"
            }
        }
        
        stage("stage 4"){
            steps{
            echo "this is stage 4"
            }
        }
    }
}