pipeline {
  agent any
  stages {
    stage('The TEst') {
      parallel {
        stage('TEST MIKE') {
          steps {
            echo 'Starting  the championship'
          }
        }
        stage('ERROR MIKE') {
          steps {
            bat 'C:/apache-maven-3.5.2/bin/mvn.cmd test'
          }
        }
      }
    }
  }
}