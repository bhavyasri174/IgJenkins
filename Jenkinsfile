pipeline {
    agent any

    tools {
        Maven 'maven'  // Ensure this name matches the one in Jenkins
    }

    stages {
        stage('Build') {
            steps {
                    sh 'mvn clean install'
                
            }
        }
    }
}
