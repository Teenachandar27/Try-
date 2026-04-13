pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // This runs the Maven build
                bat 'mvn clean package' 
            }
        }
        stage('Test') {
            steps {
                // This runs your JUnit tests
                bat 'mvn test'
            }
        }
    }
}