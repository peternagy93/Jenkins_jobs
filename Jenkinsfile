pipeline {
    agent any

    stages {
        stage('scm checkout') {
            steps {
                checkout scm
            }
        }

        stage('primul job') {
            steps {
                sh 'pwd'
                sh 'echo "Welcome to it_school Jenkins startup!" > jenkins.txt'
                sh 'ls -alh'
            }
        }

        stage('job doi') {
            steps {
                script {
                    def Age = 21
                    sh "echo I have ${Age} years and im going to be 22 next year and again 23 after that"
                }
            }
        }
    }
}