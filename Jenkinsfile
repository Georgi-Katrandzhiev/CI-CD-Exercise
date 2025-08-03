pipeline {
    agent any

    tools {
        nodejs "NodeJS" 
    }

    stages {
        stage('Install dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Run tests') {
            steps {
                sh 'npm test' 
            }
        }

        stage('Build') {
            steps {
                echo 'Build step here (if needed)'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy step here'
            }
        }
    }
}
