pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'master', credentialsId: 'Github_credentials', url: 'https://github.com/suvitha05/assignments.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
    }
}