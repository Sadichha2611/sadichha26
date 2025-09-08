pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
            git branch: 'main', credentialsId: 'c5263df8-8cad-4cad-abcd-c42ac838a345', url: 'https://github.com/Sadichha2611/sadichha26.git'
            }
        }
    stages {
        stage('Compile') {
            steps {
            bat 'javac HelloWorld.java'
            }
        }
    stages {   
        stage('Run') {
            steps {
            bat 'java HelloWorld'
            }
        }
    }
}
