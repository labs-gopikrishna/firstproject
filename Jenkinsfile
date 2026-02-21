pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                // Example for a Windows environment (batch script)
                bat 'echo Building branch: %BRANCH_NAME%'
                // bat 'mvn clean install' or 'dotnet build'
            }
        }
    }
}
