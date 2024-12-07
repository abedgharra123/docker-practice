pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                echo "build start"
                sh 'npm i'
            }
            
        }
        stage("test"){
            steps{
                echo "build start"
                sh 'npm run startdev'
            }
            
        }
    }
}