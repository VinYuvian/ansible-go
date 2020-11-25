pipeline {
  agent any
  stages {
    stage('test-step') {
      parallel {
        stage('test-step') {
          steps {
            echo 'THIS IS THE FIRST PIPELINE'
          }
        }

        stage('') {
          steps {
            echo 'declarative pipeline'
          }
        }

      }
    }

  }
}