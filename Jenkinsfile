pipeline{
    agent{
        label "testing jenkins agent"
    }
    stages{
        stage("dry-build"){
            steps{
                echo "========executing dry-build stage========"
            }
        }
        stage("dry-test"){
            steps{
                echo "========executing dry-test stage========"
            }
        }
        stage("dry-deploy"){
            steps{
                echo "========executing dry-deploy stage========"
            }
        }
        post{
            always{
                echo "========The pipeline was executedtil the end========"
            }
            success{
                echo "========A executed successfully========"
            }
            failure{
                echo "========A execution failed========"
            }
        }
    }
    post{
        always{
            echo "========always========"
        }
        success{
            echo "========pipeline executed successfully ========"
        }
        failure{
            echo "========pipeline execution failed========"
        }
    }
}
    