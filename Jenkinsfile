pipeline {
    agent any
    
    tools {nodejs "node"}
    
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
              echo 'Hello from test'
            }
        }
        stage('Deploy') {
            steps {
                echo "Deployed to AWS"
            }
        }
    }
}