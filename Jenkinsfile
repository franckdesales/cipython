pipeline{  
  agent{
    dockerfile{
      filename 'Dockerfile.build'
    }
  }
  stages{
    stage('prerequisites'){
      steps{
        echo 'pip install result'
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
