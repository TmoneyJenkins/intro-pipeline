pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Stage Hello') {
      steps {
        echo 'Hello World'
        sh 'java -version'
      }
    }
  }
}