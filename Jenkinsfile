pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning code form source code mangement'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing code against bugs and smells'
            }
        }
        stage('BuildJar') {
            steps {
                echo 'Building artefact with maven'
            }
        }
       stage('Push') {
            steps {
                echo 'Pushing artefact to DockerHub'
            }
        }
       stage('Deploy') {
            steps {
                echo 'Deploying App through K8s'
            }
        }
    }
}
