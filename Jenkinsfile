pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean install'  // Use 'bat' if running on Windows
            }
        }
    }
}
