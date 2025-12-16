pipeline {
    agent any

    stages {
        stage('Récupération du code') {
            steps {
                git 'git@github.com:asmahannechi2/ProjetStudentsManagement-DevOps-Jenkins.git'
            }
        }

        stage('Compilation Maven') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}

