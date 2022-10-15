pipeline{
    agent any
    stages{
        stage("A"){
            steps{
                echo "========executing A========"
                sh '/var/jenkins_home/hello.sh'
            }
        }
    }
    post{
        
        success{
            echo "========pipeline executed successfully ========"
        }
        
    }
}
