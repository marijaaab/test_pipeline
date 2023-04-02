pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        checkout([$class: 'GitSCM', branches: [[name: 'main']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'GH_USER_PASS', url: 'https://github.com/marijaaab/test_pipeline.git']]])
      }
    }

    stage('Build') {
      steps {
        sh 'echo Henlo!'
      }
    }
  }
}
