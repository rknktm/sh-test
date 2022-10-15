pipeline{
    agent any
    tools {
        docker
    }
    stages{
        stage("Sh-Test"){
            steps{
                echo "========executing A========"
                sh 'bash ./sh_files/hello.sh'
            }
        }

        stage("docker-build"){
            steps{
                echo "========executing dockerfile========"
                sh 'bash ./sh_files/build.sh'
            }
        }
    }
    post{
        
        success{
            echo "========pipeline executed successfully ========"
        }
        
    }
}
