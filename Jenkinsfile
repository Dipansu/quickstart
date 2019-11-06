pipeline{agent any 
  stages{ stage('Clone Repo') 
          { steps 
                  { 
				sh "sudo yum install npm"
				sh "rm -rf angular_git"
        sh "mkdir angular_git"
				sh "cd angular_git"	
        sh 'npm config ls'
				//sh "npm run build" 
				
				}
         }
      }
}
