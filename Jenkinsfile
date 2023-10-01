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
            
}
}
        

