pipeline {
  agent {
    docker {
      image 'node:10-alpine'
      args '-p 20001-20100:3000'
    }

  }
  stages {
    stage('') {
      steps {
        echo 'Hello World!!!'
      }
    }

  }
  environment {
    CI = 'true'
    Home = '.'
    npm_config_cache = 'npm-cache'
  }
}