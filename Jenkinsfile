pipeline {
    agent any

    stages {

        stage ('check if docker is install') {
            steps {
                sh 'docker --version'
            }
        }
        
        stage ('build docker images') {
            steps {
                sh 'docker build .'
            }
        }
        

    }
}