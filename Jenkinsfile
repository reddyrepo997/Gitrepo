pipeline {
    agent any 
    stages {
        stage('Clean and Test') { 
            steps {
                sh "mvn clean"
            }
        }
        stage('Test') { 
            steps {i
                sh "mvn test"
            }
        }
        stage('Deploy') { 
            steps {
                sh "mvn package"
            }
        }
    }
}
