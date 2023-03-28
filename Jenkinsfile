pipeline{
  agent any
  stages
  {
    stage('build') {
      steps{
        sh "npm pack"
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
