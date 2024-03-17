pipeline {
    agent any
    stages {
            stage('Start') {
                steps {
                    echo 'Lab_1: nginx/custom'
                }
            }
        stage('Build nginx/custom') {
            steps {
                sh 'docker build -t nginx/custom:latest .'
            }   
        }
        stage('Test nginx/custom') {
            steps {
                echo 'Pass'
            }
        stage('Text') {
            steps { 
                echo 'Type your text here :)'
        stage('build step') {
            steps {
                 echo "Build stage is running"
        stage('Load Credentials') {
            steps {
                echo "Username is $MY_CRED_USR"
                echo "Password is $MY_CRED_PSW"
        }
        stage('Deploy nginx/custom'){
            steps{
                sh "docker run -d -p 80:80 nginx/custom:latest"
            }
        }
    }
}