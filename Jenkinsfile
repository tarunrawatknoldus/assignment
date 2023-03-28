pipeline{
  agent any
  stages
  {
    stage('build') {
      steps{
        sh "npm start"
      }
    }
    stage('Deploy') {
      steps{
        echo "deploy complete"
      }
    }
   }
}
