pipeline{
  agent any
  stages{
    stage('Deploy To Dev'){
      when{
        branch 'develop'
      }
      steps{
        echo "Deploy to dev servers"
      }
    }
    
    stage('Deploy To UAT'){
      when{
        branch 'release'
      }
      steps{
        echo "Deploy to UAT servers"
      }
    }
    
    stage('Deploy To prod'){
      when{
        branch 'main'
      }
      steps{
        echo "Deploy to dev servers"
      }
    }
  }
}
