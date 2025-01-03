pipeline {
    agent any
    
    stages {
        stage('Build & Run HelloWorld') {
            steps {
                bat 'javac HelloWorld.java'
                bat 'java HelloWorld'
            }
        }
        
        stage('Build & Run Merci') {
            steps {
                bat 'javac Merci.java'
                bat 'java Merci'
            }
        }
        
        stage('Build & Run DeRien') {
            steps {
                bat 'javac DeRien.java'
                bat 'java DeRien'
            }
        }
    }
}
