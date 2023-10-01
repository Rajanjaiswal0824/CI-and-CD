pipeline {
    agent any

     parameters {
    string(name: 'STATEMENT', defaultValue: 'hello; ls /', description: 'What should I say?')
  }
    stages {
         stage('Example') {
      steps {
        /* WRONG! */
        sh("echo ${STATEMENT}")
      }
    }
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

}
        

