pipeline{
  
  agent any
  
  stages{
    
    stage("build"){
      steps{   test-repo1/hii.sh
             echo 'building the application...'
          echo "helooo" }
        }
       stage("test"){
        steps{
            
            sh 'test-repo1/hii.sh'
            echo "testing"
          }
       }
     stage("deploy"){
     steps{
      echo "deploying"
        }
       } 
     }
    }
