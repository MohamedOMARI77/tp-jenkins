pipeline {
    agent any
    
    stages {
        stage('Build & Run HelloWorld') {
            steps {
                sh 'javac HelloWorld.java'
                sh 'java HelloWorld'
            }
        }
        
        stage('Build & Run Merci') {
            steps {
                sh 'javac Merci.java'
                sh 'java Merci'
            }
        }
        
        stage('Build & Run DeRien') {
            steps {
                sh 'javac DeRien.java'
                sh 'java DeRien'
            }
        }
    }
}
