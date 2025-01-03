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
        
        stage('Build & Run Derien') {
            steps {
                bat 'javac Derien.java'
                bat 'java Derien'
            }
        }
    }
}
