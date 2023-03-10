pipeline {
  agent any
  stages {
    stage("Huang - Build Docker Image"){
	    steps{
        sh "echo Integrating Jenkins pipeline with github webhook using jenkinsfile"
        sh "ls"
      }
    }
    stage("Huang - Login to Dockerhub"){
      steps {
        sh "echo deployment stage has been completed"
        sh "echo good bye"
        sh "docker build -t test05 ."
      }
    }
    stage("Huang - Push image to dockerhub"){
      steps {
        sh "echo hi"
      }
    }
	}
}
