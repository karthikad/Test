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
        bat './jenkins/scripts/test.sh'
      }
    }

  }
}