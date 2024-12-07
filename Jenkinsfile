pipeline{
    agent any;
    stages{
        stage("build"){
            steps{
                echo "build start"
                docker-compose up --build
            }
            
        }
    }
}