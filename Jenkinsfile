pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'Starting '
          }
        }
        stage('error') {
          steps {
            bat 'C:/apache-maven-3.5.2/bin/mvn.cmd test'
          }
        }
      }
    }
  }
}