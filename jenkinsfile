pipeline {
    agent any
    stages {
        stage('SCM Checkout') {
            steps {
                echo "PIPELINE FROM GITHUB"
                echo "Starting Checkout.."
                echo "Checkout Successful"
            }
        }
        
        stage('Build') {
            steps {
                echo "Starting Build.."
                echo "Build Successful"
            }
        }
        stage('Test') {
            steps {
                echo "Starting Test.."
                echo "Test Successful"            
            }
        }
        stage('Deploy') {
            steps {
                echo "Starting Deploy.."
                echo "Deploy Successful" 
                }
        }
    }
}
