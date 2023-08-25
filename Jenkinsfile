pipeline{
  agent any
  stages{
      stage('Checkout code Stage') {
        steps {
            checkout scm
        }
    }

    stage("Copy files to docker container"){
      steps{
        echo 'Copying notebooks and databases files to container'
        
      }
    }

    stage("Run all cells script"){
      steps{
        echo 'running cells...'

        
      }
    }
  }
}
