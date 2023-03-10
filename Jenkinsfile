pipeline {
    agent any
    stages {
        stage("build"){
	    steps{
	        sh "echo Integrating Jenkins pipeline with github webhook using jenkinsfile"
                sh "ls"
		sh "apt-get install docker-ce docker-ce-cli containerd.io"
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
