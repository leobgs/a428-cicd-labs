pipeline {
    agent{
        docker {
            image 'node:16-buster-slim'
            args '-p 5000:5000'
        }
    }

    stages {
        stage('Build'){
            steps{
                sh 'npm install'
            }
        }
    }
}