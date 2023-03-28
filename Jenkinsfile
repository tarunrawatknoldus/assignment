pipeline{
  agent any
  triggers{
    cron('* * * * *')
  }
  stages
  {
    stage ('build') {
      sh "npm pack"
      sh "npm install"
    }
    stage ('Deploy') {
      echo "deploy complete"
    }
   }
}
