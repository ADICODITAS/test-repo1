pipeline{
  agent any
  stages{
    stage("build"){
      steps {
          chmod +x 'hii.sh'
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
