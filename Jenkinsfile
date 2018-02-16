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
        stage('') {
          steps {
            bat 'C:/Tools/Jenkins, Maven_E_16-2-18/apache-maven-3.5.2/bin/mvn.cmd test'
          }
        }
      }
    }
  }
}