pipeline {
  agent {
    node {
      label 'node1'
    }

  }
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo "stage 1"'
          }
        }

        stage('stage2') {
          steps {
            sh 'echo "stage2"'
          }
        }

      }
    }

  }
}