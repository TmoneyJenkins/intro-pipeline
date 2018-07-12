pipeline {
  agent {
    label 'jdk8'
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