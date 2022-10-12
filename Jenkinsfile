pipeline {
  agent any
  stages {
    stage('Check Code') {
      steps {
        git(url: 'https://github.com/moureg2001/curriculum-app', branch: 'dev')
      }
    }

    stage('') {
      steps {
        sh 'ls -la'
      }
    }

  }
}