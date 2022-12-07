pipeline{
    agent any
    stages{
        stage("Test"){
            steps{
                echo "========executing Test========"
            }
        }
        stage("Build"){
            steps{
                echo "========executing Build========"
            }
        }
        stage("Deploy on Test"){
            steps{
                echo "========deploying on Test========"
            }
        }
        stage("Deploy on Prod"){
            steps{
                echo "========deploying on Prod========"
            }
        }
    }
    post{
        always{
            echo "========Pipeline build %BUILD_ID%========"
        }
        success{
            echo "========pipeline executed successfully ========"
        }
        failure{
            echo "========pipeline execution failed========"
        }
    }
}