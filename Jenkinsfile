pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                checkout scm
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t my-website .'
            }
        }

        stage('Run Docker Container') {
            steps {
                sh 'docker rm -f my-container || true'
                sh 'docker run -d --name my-container -p 80:80 my-website'
            }
        }
    }
}
