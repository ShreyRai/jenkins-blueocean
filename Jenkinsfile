pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        sh 'echo "Hello this is the say hello stage"'
      }
    }

    stage('Add parameters') {
      parallel {
        stage('Add parameters') {
          steps {
            echo 'This is it'
          }
        }

        stage('test1') {
          steps {
            echo 'this is eat'
          }
        }

      }
    }

  }
}