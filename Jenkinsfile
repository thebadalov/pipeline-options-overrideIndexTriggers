pipeline{
    agent any
    options {
      timestamps()
      overrideIndexTriggers(false)
    }
    stages{
        stage("Build"){
           steps{
               timestamps {
                   echo "Hello World 2" 
               }
           }
        }
    }
}

