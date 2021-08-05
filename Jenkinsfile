pipeline {
  agent any
  stages {
    stage('hello') {
      parallel {
        stage('hello') {
          steps {
            echo 'hello'
          }
        }

        stage('deploy') {
          steps {
            sh 'echo "deploy"'
          }
        }

      }
    }

    stage('test') {
      steps {
        echo 'testing'
      }
    }

  }
}