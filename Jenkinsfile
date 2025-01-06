pipeline {
    agent any

    stages {
        stage('git') {
            steps {
            git branch: 'main', url: 'https://github.com/Deepakg-code/maven-demo.git'
            }
        }
        
        stage('maven') {
            steps {
            sh 'mvn clean package'
            }
        }        
    }
}