pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                a = 10
                b = 20
                echo $(( a + b )
                echo "First Step";
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

