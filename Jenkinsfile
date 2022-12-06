pipeline {
    agent any
    
    stages {
        stage('Stage 1') {
            steps {
                sh "ls"
            }
        }
        stage('Stage 2') {
            steps {
                sh "pwd"
            }
        }
        stage('Stage 3') {
            steps {
                sh "touch stage3.txt"
            }
        }
        stage('Stage 4') {
            steps {
                sh "mkdir stage4"
                sh "mv stage3.txt stage4"
            }
        }
    }
}
