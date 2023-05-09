pipeline {
    agent any
     stages{
      stage('Build'){
       steps {
         echo "Build Step"
         sleep 10
       }
    }
    stage('test'){
       steps {
         echo "Test Step "
       }
    }
    stage('Deploy'){
       steps {
         echo "Deploy Step"
       }
    }
    stage('Docker'){
       steps {
         echo "Image step"
       }
    }
   }

}
