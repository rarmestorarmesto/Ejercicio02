pipeline {
    //agent none
    agent any
    tools {
        maven 'LocalMaven' 
        java 'LocalJDK8'
    } 	
    stages {	
	    stage('Stage') {
		    steps {
			git 'ithub.com/rarmestorarmesto/Spring3MVC.git'
                	echo 'This stage will be executed first'
          		}
      	    }
   	    stage('BUILD') {
		    steps {
			bat "MiMavem.bat"
			echo "BUILD"
		    }
		}
   	    stage('QUALITY') {
		    steps {
			bat "Quality.bat"
			echo "QUALITY"
		    }
		}
    }
}
