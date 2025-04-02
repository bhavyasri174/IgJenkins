pipeline{
  agent any
  stages{
    stage('Compile and clean'){
      steps{
        bat 'mvn compile'
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
