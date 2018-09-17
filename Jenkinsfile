pipeline {
  agent any
  stages {
    stage('DEV') {
      steps {
        echo 'Push to QA'
      }
    }
    stage('QA') {
      steps {
        echo 'Push To Production'
      }
    }
    stage('Production') {
      steps {
        echo 'push'
      }
    }
  }
}