pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        echo 'Building app'
      }
    }

    stage('List Files') {
      steps {
        sh 'ls -l'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing app'
      }
    }
  }
}
