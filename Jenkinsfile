pipeline {
  agent any
  stages {
    stage('DEV') {
      parallel {
        stage('DEV') {
          steps {
            echo 'Push to QA'
          }
        }
        stage('bla') {
          steps {
            waitUntil() {
              sh '''pipeline {
    node any
    stages {
        stage(\'one\') {

        }
        stage(\'two\') {
        }
    } // end of stages block
    post {
        <checkstyle step>
    } //post block in pipeline scope
}'''
              }

            }
          }
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