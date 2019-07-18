pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 1234:1234' 
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
