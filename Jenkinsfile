pipeline{
  agent any
  stages{
    stage('clone'){
      steps{
        git branch:'main',url:'https://github.com/Trineshpasupununti/Calculator.git';
      }
    }
    stage('compile'){
      steps{
        sh 'javac Calculator.java'
      }
    }
    stage('build'){
      step{
        sh 'java Calculator 25 5'
      }
    }
  }
}
        
