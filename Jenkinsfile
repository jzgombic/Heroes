pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'ng serve --proxy-config proxy.conf.json --port 7626 --open'
      }
    }

  }
}