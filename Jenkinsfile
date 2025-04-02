pipeline{
  agent any
   tools {
        maven 'M3'  // Use the Maven tool name configured in Jenkins
    }
  stages{
    stage('Compile and clean'){
      steps{
        sh 'mvn clean compile'
      }
    }
    stage('Test'){
      steps{
        echo 'Test'
      }
    }
    stage('Scan'){
      steps{
        echo'Scan'
      }
    }
  }
}
