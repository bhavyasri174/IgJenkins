pipeline {
    agent any

    tools {
        maven 'Maven_3.9.9'  // Ensure this name matches the one in Jenkins
    }

    stages {
        stage('Build') {
            steps {
                withMaven(maven: 'Maven_3.9.9') {  // Correctly wrapped in 'steps'
                    sh 'mvn clean install'
                }
            }
        }
    }
}
