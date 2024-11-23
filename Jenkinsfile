pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                // Cloner le dépôt Git
                git 'https://github.com/MohamedOMARI77/tp-jenkins.git'
            }
        }
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
