pipeline {
  agent any
  stages {
    stage('A') {
      parallel {
        stage('A1') {
          steps {
            echo '111'
          }
        }
        stage('A2') {
          steps {
            echo '222'
          }
        }
        stage('A3') {
          steps {
            echo '33'
          }
        }
      }
    }
    stage('B') {
      parallel {
        stage('B1') {
          steps {
            echo 'b1'
          }
        }
        stage('B2') {
          steps {
            echo 'B2'
          }
        }
      }
    }
  }
}