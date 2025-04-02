pipeline{
  agent any
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
