pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                echo 'Repository already cloned'
            }
        }

        stage('Run Python Script') {
            steps {
                bat 'python sample.py'
            }
        }

    }
}