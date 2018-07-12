pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Stage Hello') {
      steps {
        echo "Hello ${MY_NAME}!"
        echo "${TEST_USER_USR}"
        echo "${TEST_USER_PSW}"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Tom'
    TEST_USER = credentials('test-user')
  }
}