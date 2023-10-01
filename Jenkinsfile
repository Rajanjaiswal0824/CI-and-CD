pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                a = 10
                b = 20
                sum=$((num1 + num2))
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
}

