pipeline{agent any 
  stages{ stage('Clone Repo') 
          { steps 
                  { 
				 
				sh "rm -rf angular_git"
        sh "mkdir angular_git"
				sh "cd angular_git"	
				sh "npm run build" 
				
				}
         }
      }
}
