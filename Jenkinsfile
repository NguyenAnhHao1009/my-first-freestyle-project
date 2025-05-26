pipeline {
    agent any

    tools {
        jdk 'jdk-17'
    }

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/NguyenAnhHao1009/my-first-freestyle-project.git'
            }
        }

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