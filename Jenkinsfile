pipeline{
    agent any
    options {
      timestamps()
      //overrideIndexTriggers(true)
    }
    stages{
        stage("Build"){
           steps{
               timestamps {
                   echo "Hello World 1" 
               }
           }
        }
    }
}

