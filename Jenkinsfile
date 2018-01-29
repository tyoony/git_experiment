pipeline {
  agent {
    node {
      label 'master'
    }
    
  }
  stages {
    stage('download latest binary') {
      steps {
        sh '''echo "this is download latest binary step"
'''
      }
    }
    stage('flashing binary') {
      steps {
        sh 'echo "this is flashing step"'
      }
    }
  }
}