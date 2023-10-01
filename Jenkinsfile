pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Sum $Sum";
            }
        }
        stage('Test') {
            steps {
                echo "Second Step";
            }
        }
        stage('Deploy') {
            steps {
                echo "Third Step";
            }
        }
    }
    post{
        step("Email Notification"){
            echo "Email Notification";
        }
    }
            
}
        

