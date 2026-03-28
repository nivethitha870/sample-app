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
                sh 'mvn clean package -DskipTests'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage executed'
            }
        }

    }
}
