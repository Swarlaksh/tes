pipeline{
  agent any 
  stages{
    stage('CICD'){
      steps{
         sh 'pip install boman-cli==1.4'
         sh '~/.local/bin/boman-cli-uat -a run -cicd jenkins'
      }
    }
  }
}
