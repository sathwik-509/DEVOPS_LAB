pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/sathwik-509/DEVOPS_LAB.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
                // Add your build commands, e.g., Maven, npm, etc.
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                // Add test commands here
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Your deployment logic here (e.g., copy files, restart server)
            }
        }
    }
}
