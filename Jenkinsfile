pipeline {
  agent any
  stages {
    stage('testing') {
      steps {
        echo 'hello test area'
        bat 'mkdir test2'
      }
    }

    stage('uat') {
      steps {
        echo 'hello uat area'
        bat 'mkdir test3'
      }
    }

  }
  environment {
    building = 'hello environment area'
  }
}