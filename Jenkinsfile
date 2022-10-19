pipeline{
    agent any
    tools
    {
        maven "maven"
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