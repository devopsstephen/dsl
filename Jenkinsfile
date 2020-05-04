pipeline{
    agent any
    stages{
        
        stage ('checkout'){
            
            steps{
                
                echo 'hi this is DSL'
            }
            
        }

    stage ('build'){
     
      steps{

         echp "mvn build"
}

      }
    
   stage('deploy'){

        steps{
      echo 'deploy'
}

}



   }     
        
    }
