pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        git url: 'https://github.com/marijaaab/test_pipeline.git'
      }
    }

    stage('Build') {
      steps {
        sh 'echo Henlo!'
      }
    }
  }
}
