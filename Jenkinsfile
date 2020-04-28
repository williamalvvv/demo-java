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
        sh 'mvn test'
      }
    }

    stage('Deliver') {
      steps {
        sh 'echo \'Delivered successfully\''
        sh 'sudo cp target/demo.war /home/sysadmin/'
      }
    }

  }
}