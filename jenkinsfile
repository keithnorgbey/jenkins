pipeline {
	 agent any

	 stages {
	   stage('Cloning') {
		steps {
		  git url: ' https://github.com/keithnorgbey/webserver.git', branch: 'main'
		}
	}
    }
	  stage('Building image') {
		steps {
		  sh  'docker build -t keith/keithserver2 .'
		   }
	}
 }
		  
	   
    

