pipeline{  
  agent none
  stages{
    stage('prerequisites'){
      agent{
        label{  image 'django'  }
      }
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
