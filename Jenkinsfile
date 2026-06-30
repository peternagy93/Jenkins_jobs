pipeline {
    agent any
    stage('scm checkout') {
        steps {
            checkout scm
        }
    }

    stages {
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
                    sh "echo I have ${Age} years"
                }
            }
        }
    }
}