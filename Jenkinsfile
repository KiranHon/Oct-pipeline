pipeline {
agent any
stages {
         stage { 'print a message' }
		 steps { sh 'echo job-is-building' }
		 
		 stage {'print-second-message' }
		 	steps {sh 'echo package-is-deploying'}
		 
		 stage { 'print last stage' }
		 	steps { sh 'echo deploy-to-prod'}
		 
}
}		 
