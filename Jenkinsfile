pipeline{
    agent any
    tools
    {
        maven "Maven"
    }
    stages{
        stage('checkout'){
          steps{  
            checkout scm;
           }
        }

         stage('Execute Maven'){
            sh 'mvn package'
         }
    }
}