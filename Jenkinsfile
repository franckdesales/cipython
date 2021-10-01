pipeline{  
  agent none
  stages{
    stage('prerequisites'){
      agent{
        docker{  image 'python:3.9-slim-buster'  }
      }
      steps{
        sh 'apt-get update'
        sh 'apt-get install --no-install-recommends -y build-essential libpq-dev'
        
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
