pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'ng build --prod'
      }
    }

    stage('NPM Install') {
      steps {
        bat 'npm install'
      }
    }

  }
}