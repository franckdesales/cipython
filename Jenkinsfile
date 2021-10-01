pipeline{  
  agent{
    dockerfile{
      filename 'Dockerfile.build'
    }
  }
  stages{
    stage('prerequisites'){
      steps{
        sh 'docker ps -a'
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
