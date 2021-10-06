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
        sh 'pytest'
        sh 'coverage run -m pytest'
        sh 'coverage html'
      }
    }

    stage('test'){
      steps{
        sh 'pytest'
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
