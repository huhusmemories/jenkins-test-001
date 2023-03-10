pipeline {
  agent any
  stages {
    stage("Huang - Build Docker Image"){
	    steps{
        sh "echo ${username} ${password}"
        sh "docker build -t test05 ."
      }
    }
    stage("Huang - Login to Dockerhub"){
      steps {
        sh "Logging in to Dockerhub"
        sh "docker login"
        sh "${username}"
        sh "${password}"
      }
    }
    stage("Huang - Push image to dockerhub"){
      steps {
        sh "Pushing image to dockerhub"
        sh "docker image push ${username}/test05"
      }
    }
	}
}
