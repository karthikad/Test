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
      environment {
        CI = 'true'
      }
      steps {
        retry(count: 2)
      }
    }

    stage('Deliver') {
      steps {
        echo 'HelloWorld'
      }
    }

  }
}