pipeline {
    agent any
    stages {
        stage("build"){
	    steps{
	        sh "echo Integrating Jenkins pipeline with github webhook using jenkinsfile"
                sh "ls"
		}
            }
        stage("deployment"){
             steps {
                 sh "echo deployment stage has been completed"
                 sh "echo good bye"
		 sh "docker build -t test05 ."
                 }
	    }
	}
}
