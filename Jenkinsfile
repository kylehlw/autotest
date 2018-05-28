pipeline {
  agent any
  stages {
    stage('start') {
      parallel {
        stage('start') {
          steps {
            sh 'echo "This is the first step."'
          }
        }
        stage('bash') {
          steps {
            echo 'hello step2'
          }
        }
      }
    }
  }
}