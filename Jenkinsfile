pipeline {
    agent {
    node{
        lable 'AGENTT1'
    }
  }
    stages {
        stage('Build') { 
            steps {
                echo "Building"
            }
        }
        stage('Test') { 
            steps {
                echo "testing"
            }
        }
        stage('Deploy') { 
            steps {
                echo "deploying"
            }
        }
    }
}