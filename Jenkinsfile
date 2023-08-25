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
     //   sh ' docker cp "Collab recommendation sys.ipynb" mlops_container:/home/belhassen/work/"Collab recommendation sys.ipynb" '
     //   sh ' docker cp JFM.xlsx mlops_container:/home/belhassen/work/JFM.xlsx '
    //    sh ' docker cp "LIGHT CONTENT REC.ipynb" mlops_container:/home/belhassen/work/"LIGHT CONTENT REC.ipynb" '
    //    sh ' docker cp PFE_LIGHT.ipynb mlops_container:/home/belhassen/work/PFE_LIGHT.ipynb '
    //    sh ' docker cp "Word2Vec COLAB REC.ipynb" mlops_container:/home/belhassen/work/"Word2Vec COLAB REC.ipynb" '
     //   sh ' docker cp colab_rec_df.xlsx mlops_container:/home/belhassen/work/colab_rec_df.xlsx '
       // sh ' docker content_rec_df.xlsx mlops_container:/home/belhassen/work/content_rec_df.xlsx '
      }
    }

    stage("Run all cells script"){
      steps{
        echo 'running cells...'
   //     sh 'jupytext --execute "LIGHT CONTENT REC.ipynb"'
   //     sh 'jupytext --execute "Collab recommendation sys.ipynb"'
   //     sh 'jupytext --execute "Word2Vec COLAB REC.ipynb"'


        
      }
    }
  }
}
