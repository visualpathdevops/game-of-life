pipeline {
 agent any 
   stages {
     stage ('compile stage') {      
      steps {
            sh 'mvn clean compile'
            }
           }
        stage ('Test Stage') {
        steps {
                 sh 'mvn test'
            }
           }
     stage ('package Stage') {
        steps {
              sh 'mvn package'
            }
           }
         }
        } 
