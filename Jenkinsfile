pipeline{
    agent any;
    stages{
        stage("build"){
            echo "build start"
            docker-compose up --build
        }
    }
}