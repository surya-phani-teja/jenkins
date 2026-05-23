pipeline {
    agent { label 'AGENTT1' }

    stages {
        stage('Check Agent') {
            steps {
                sh 'hostname'
                sh 'whoami'
                sh 'pwd'
                echo "Agent connected successfully"
            }
        }
    }
}