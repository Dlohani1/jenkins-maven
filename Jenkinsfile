pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                sh git clone "https://github.com/Dlohani1/jenkins-maven.git"
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
