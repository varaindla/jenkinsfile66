pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'i want to print'
          }
        }

        stage('deploy') {
          steps {
            echo 'deployed'
          }
        }

      }
    }

    stage('build') {
      steps {
        echo 'i want to build'
      }
    }

  }
}