pipeline{
  agent any 
  stages{
    stage('CICD'){
      steps{
         sh 'sudo pip install --user --extra-index-url https://test.pypi.org/simple/ boman-cli-uat==0.12 '
         sh 'sudo ~/.local/bin/boman-cli-uat -a run '
      }
    }
  }
}
