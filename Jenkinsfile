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
        sh 'coverage run -m pytest'
        sh 'coverage html'
      }
    }

    stage('packaging'){
      steps{
        echo 'packaging'
      }
    }
  }
}
