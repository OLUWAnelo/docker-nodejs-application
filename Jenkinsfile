pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/OLUWAnelo/docker-nodejs-application', branch: 'main')
      }
    }

    stage('Log') {
      steps {
        sh 'ls -la'
      }
    }

    stage('FrontEnd Test') {
      steps {
        sh '''ls docker-nodejs-application 
'''
      }
    }

  }
}