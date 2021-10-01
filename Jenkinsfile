pipeline{  
  agent none
  stages{
    stage('prerequisites'){
      agent{
        docker{  image 'django'  }
      }
      steps{
        sh 'pip install -r ./transparencyportal/requirements/production.txt'
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
