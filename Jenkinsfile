pipeline {
    agent any
    tools {
        maven 'maven-3.9.6'
    }
    stages {
        stage('Clean and Install') {
            steps {
               sh 'mvn clean package'
            }
        }
        stage('Package') {
            steps {
               sh 'mvn package'
            }
        } 
    }
}
