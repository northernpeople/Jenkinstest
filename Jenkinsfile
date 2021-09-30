pipeline {
    agent any
	tools{
		maven 'maven3_8_2'
	}
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'mvn --version'
            }
        }
        stage('Test') {
            steps {
                echo 'Te2sting..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
        
         stage('post Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
        
        
    }
}
