pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git credentialsId: 'dlohani1@gmail.com', url: 'https://github.com/Dlohani1/jenkins-maven.git'
                sh "git branch -a"
            }
        }
        stage('Compile') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Test') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
