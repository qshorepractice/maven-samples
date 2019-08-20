pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        echo 'Compiled'
      }
    }
    stage('Compile') {
      steps {
        bat 'mvn compile'
      }
    }
  }
}