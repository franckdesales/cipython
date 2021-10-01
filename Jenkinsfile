pipeline{  
  agent{
        docker{  image 'django'  }
      }
  stages{
    stage('prerequisites'){
      steps{
        echo 'build'
        sh 'python --version'
      }
    }

    stage('test'){
      steps{
        echo 'test'
      }
    }

    stage('packaging'){
      steps{
        echo 'packaging'
      }
    }
  }
}
