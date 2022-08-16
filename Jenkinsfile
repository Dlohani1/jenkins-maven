pipeline {
    agent any
    
    tools {
           
           maven:"maven"
         
        }
    stages {
        stage('Clone') {
           
            steps {
                git credentialsId: '41409b56-475f-4e73-997d-34458a2c7315', url: 'https://github.com/Dlohani1/jenkins-maven.git'
            }
        }
        stage('Compile') {
            
            steps {
                
                sh "${mvnHome}/bin/mvn compile"
               
            }
        }
        stage('Test') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
