'pipeline {
    agent any

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
