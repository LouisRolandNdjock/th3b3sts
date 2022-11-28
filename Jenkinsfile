pipeline {
  
  agent any
  
  stages{
    stage ('Build'){ 
      steps{
        echo "Building the project"
      }
    }
  }
     post{
       success{
         emailext body: 'Email sent out from Jenkins', subject: 'Test Email', to: 'devopsstudygroup@gmail.com'
       }
     }
}
