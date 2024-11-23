pipeline {
    agent any
    stages {
        stage('Compile') {
            steps {
                sh 'javac HelloWorld.java Merci.java Derien.java'
            }
        }
        stage('Run HelloWorld') {
            steps {
                sh 'java HelloWorld'
            }
        }
        stage('Run Merci') {
            steps {
                sh 'java Merci'
            }
        }
        stage('Run DeRien') {
            steps {
                sh 'java Derien'
            }
        }
    }
}
