pipeline{
    agent {
        dockerContainer {image 'node:22'}
    }
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