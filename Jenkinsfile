pipeline { 
  
   agent any

   stages {
   
     stage('Build') { 
        steps { 
           sh 'echo "This is build stage..."'
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
