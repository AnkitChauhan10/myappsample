pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                // Your build steps go here
                echo 'Building...'
            }
        }
        
        stage('Test') {
            steps {
                // Your test steps go here
                echo 'Testing...'
            }
        }
        
        stage('Deploy') {
            steps {
                // Your deployment steps go here
                echo 'Deploying...'
            }
        }
    }
    
    post {
        success {
            echo 'Pipeline succeeded! Do something here...'
        }
        failure {
            echo 'Pipeline failed! Do something else here...'
        }
    }
}
