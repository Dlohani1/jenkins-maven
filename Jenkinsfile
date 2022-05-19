pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git credentialsId: 'Dlohani1', url: 'https://github.com/Dlohani1/jenkins-maven.git'
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
