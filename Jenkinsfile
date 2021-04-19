pipeline {
    agent any 
    stages {
        stage('Code Analysis') {
            steps {
                echo 'Code Analysis' 
            }
        }		
        stage('Unit Testing') {
            steps {
                echo 'Unit Testing' 
            }
        }
		stage('Packaging') {
            steps {
                echo 'Building Jar file' 
            }
        }
        stage('Dockerization') {
            steps {
                echo 'Building docker image' 
            }
        }
		stage('Deploy') {
            steps {
                echo 'Deploying to K8s' 
            }
        }
    }
}
