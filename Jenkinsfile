pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
              echo'building'
              sh 'make build'
           }
      }
      stage('Test'){
      steps{
              echo'testing'
              sh 'make test'
           }
      }
       stage('Deploy'){
      steps{
              echo'deploying'
              sh 'make deploy'
           }
      }
     }
   }
