pipeline{
    agent any
    stages{
        stage("Checkout Code"){
            steps{
                echo "Checkout code"
            }
        }
        stage("Build"){
            steps{
                echo "Build project"
            }
        }
         stage("Test"){
            steps{
                echo "Test"
            }
        }
        stage("Deploy-Int"){
            steps{
                echo "Deploy Int Environment"
            }
        }
        stage("Deploy-QA"){
            steps{
                echo "Deploy QA Environment"
            }
        }
         stage("Deploy-UAT"){
            steps{
                echo "Deploy UAT Environment"
            }
        }
        stage("Deploy-Prod"){
            steps{
                echo "Deploy Prod Environment"
            }
        }
    }
}
