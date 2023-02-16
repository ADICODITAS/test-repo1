pipeline{
  agent any
  stages{
    stage("build"){
      steps {
      sh './ https://github.com/ADICODITAS/test-repo1/blob/main/hii.sh'
      echo 'building the application...'
      echo "helooo"
      }
        }
       stage("test"){
        steps{
          sh './hii.sh'
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
