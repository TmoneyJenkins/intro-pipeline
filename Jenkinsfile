pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Stage Hello') {
      steps {
        echo "Hello ${MY_NAME}!"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Tom'
  }
}