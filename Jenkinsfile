pipeline{
  

  stages{
    stage('prerequisites'){
      agent{
        docker{  image 'django'  }
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
