pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sleep 2
      }
    }

    stage('Test') {
      agent any
      steps {
        echo 'Hello'
      }
    }

    stage('Deliver') {
      steps {
        echo 'HelloWorld'
      }
    }

  }
}