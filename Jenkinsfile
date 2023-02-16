pipeline{
  agent any
  stages{
    stage("build"){
      steps {
      sh 'az login'
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
