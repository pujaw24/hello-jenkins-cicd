pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/pujaw24/hello-jenkins-cicd.git'
            }
        }

        stage('Hello World Step') {
            steps {
                echo "Hello World from Jenkins CI/CD 🚀"
                sh "cat index.txt"
            }
        }
    }
}