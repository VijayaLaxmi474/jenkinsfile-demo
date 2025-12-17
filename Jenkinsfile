pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        echo 'Building app'
      }
    }

    stage('Docker Build') {
      steps {
        sh 'docker build -t myapp:1.0 .'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing app'
      }
    }
  }
}
