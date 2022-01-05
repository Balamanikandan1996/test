pipeline {
    agent any
	stages {
	    stage ('Build and Deployment') {
	        steps {
                   echo 'Build stage is success'
                   script {
                      sh '''
                         docker-compose up --build -d
                         '''
                   }
               }
            }  
	}
}
