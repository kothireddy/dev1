pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'done testing the application'
      }
    }
    stage('build') {
      steps {
        sh 'print " build is successful"'
      }
    }
    stage('finish') {
      steps {
        sh 'print "done"'
      }
    }
  }
}