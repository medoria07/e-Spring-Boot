pipeline {
    agent any

    stages {
        stage('compile') {
            steps {
                sh 'mvn clean'
		sh 'mvn compile'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
