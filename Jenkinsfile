pipeline {
    agent any
    stages {
        stage('Compile') {
            steps {
                // Compiler les classes Java
                sh 'javac HelloWorld.java Merci.java Derien.java'
            }
        }
        stage('Run HelloWorld') {
            steps {
                // Exécuter HelloWorld
                sh 'java HelloWorld'
            }
        }
        stage('Run Merci') {
            steps {
                // Exécuter Merci
                sh 'java Merci'
            }
        }
        stage('Run DeRien') {
            steps {
                // Exécuter DeRien
                sh 'java Derien'
            }
        }
    }
}
