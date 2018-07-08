pipeline {
  agent any
  stages {
    stage('build-snapshot') {
      parallel {
        stage('hello world') {
          steps {
            sh '''echo hello world
'''
          }
        }
        stage('unit-test') {
          steps {
            echo 'Running unit tests'
          }
        }
        stage('another step') {
          steps {
            echo 'Running unit tests'
          }
        }
      }
    }
  }
}
