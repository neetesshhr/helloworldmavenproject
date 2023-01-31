pipeline{
    agent any
    // tools
    // {
    //     maven "maven"
    // }
    stages{
        stage('checkout'){
          steps{  
            checkout scm;
           }
        }

        //  stage('Execute Maven'){
        //     steps{
        //     sh 'mvn package'
        //  }
        //  }
        stage('hello world'){
            steps{
                echo "Hello world"
            }
        }

    }
}