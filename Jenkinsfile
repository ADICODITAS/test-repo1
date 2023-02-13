pipeline{
  agent any
  stages{
    stage("build"){
      steps {
      
      echo 'building the application...'
        git clone https://github.com/ADICODITAS/test-repo1.git
      
      }
        }
       stage("test"){
        steps{
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
