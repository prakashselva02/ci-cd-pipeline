pipeline {
    agent any
    tools { 
        maven 'Maven' 

    }
         stages {
           stage ('compile') {
            steps {
                bat "mvn compile" 
            }
         }
          stage ('test') {
            steps {
                 bat "mvn test" 
            }
         }
          stage ('package') {
            steps {
                bat "mvn package" 
            }
         }
          stage ('Build') {
            steps {
                bat "mvn install" 
            }
         }
    
    }
}
