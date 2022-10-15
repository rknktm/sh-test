pipeline{
    agent any
    stages{
        stage("A"){
            steps{
                echo "========executing A========"
                sh 'hello.sh'
            }
        }
    }
    post{
        
        success{
            echo "========pipeline executed successfully ========"
        }
        
    }
}
