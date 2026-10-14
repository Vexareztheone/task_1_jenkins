pipeline{
    agent any
    stages{
        stage("Install NPM dependencies"){
            steps{
                bat "npm install"
            }
        }
        stage("Run test"){
            steps{
                bat "npm test"
            }
        }

    }
}