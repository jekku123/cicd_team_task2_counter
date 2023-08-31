pipeline {
    agent any
    
    tools {nodejs "node"}
    
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
                sh 'npm run build'
            }
        }
        stage('Test') {
            steps {
                echo "No tests"
              }
            }
        stage('Deploy') {
            steps {
                echo "Deployed to AWS"
            }
        }
    }
}