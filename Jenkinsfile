pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           echo $PATH
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
