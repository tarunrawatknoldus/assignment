pipeline{
  agent any
  triggers{
    cron('* * * * *')
  }
  stages
  {
    stage('build') {
      steps{
        sh "npm pack"
        sh "npm install"
      }
    }
    stage('Deploy') {
      steps{
        echo "deploy complete"
      }
    }
   }
}
