pipeline{
  agent any
  stages{
    stage('Compile and clean'){
      steps{
        bat 'mvn clean'
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
