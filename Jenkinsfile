pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn package'
      }
    }

    stage('Test') {
      steps {
        sh 'echo \'Test succeded\''
      }
    }

    stage('Deliver') {
      steps {
        sh 'echo \'Delivered successfully\''
      }
    }

  }
}