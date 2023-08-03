pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'mvn clean package' 
            }
        }
        stage('Test') { 
            steps {
                echo 'Hello, JDK'
                sh 'java -version'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'I will deploy'
            }
        }
    }
}
