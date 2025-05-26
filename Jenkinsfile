pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh 'javac MyLunch.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java MyLunch'
            }
        }
    }
}