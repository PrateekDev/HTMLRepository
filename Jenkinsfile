pipeline {
  agent any
  stages {
    stage('First') {
      parallel {
        stage('First') {
          steps {
            echo 'Hello There'
          }
        }
        stage('step 2') {
          steps {
            echo 'hello there again'
          }
        }
      }
    }
  }
}