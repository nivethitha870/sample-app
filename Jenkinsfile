pipeline {
    agent any
    
    stages {
        
        stage('SCM Checkout') {
            steps {
                echo 'Checking source code'
            }
        }
        
        stage('Build') {
            steps {
                sh 'mvn clean compile'
            }
        }
        
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        
    }
}
