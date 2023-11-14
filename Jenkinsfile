pipeline {
    agent {
        docker {
            image 'node:20.9-alpine3.17' 
            args '-p 3000:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}