pipeline {
    agent any
    stages {
        stage('clean and compile') {
            steps {
                echo 'Hello, Maven'
                sh 'mvn clean  compile'
            }
        }
        stage('Example Test') {
            
            steps {
                echo 'Hello, JDK'
               
            }
        }
    }
}
