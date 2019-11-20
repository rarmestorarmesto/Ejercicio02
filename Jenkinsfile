pipeline {
    //agent none
    agent any
    tools {
        maven 'LocalMaven' 
        java 'LocalJDK8'
    } 	
    stages {	
	    stage('Non-Parallel Stage') {
          	steps {
                	echo 'This stage will be executed first'
          		}
      	}
    }
}
