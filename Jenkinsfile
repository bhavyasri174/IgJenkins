pipeline {
    agent any
    tools {
        maven 'Maven_3.9.9'  // Use the configured Maven tool in Jenkins
    }
    stages {
        stage('Build') {
            steps {
                bat 'mvn clean install'  // Use 'sh' instead of 'bat' for Linux/Mac
            }
        }
    }
}
