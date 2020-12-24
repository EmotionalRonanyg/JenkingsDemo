pipeline {
  agent any
  stages {
    stage('Build step') {
      parallel {
        stage('Build step') {
          steps {
            echo 'Building'
          }
        }

        stage('Build step 2') {
          steps {
            echo 'Building 2'
          }
        }

      }
    }

    stage('Test step') {
      parallel {
        stage('Test step') {
          steps {
            echo 'Testing'
          }
        }

        stage('Test step 2') {
          steps {
            echo 'Testing 2'
          }
        }

      }
    }

    stage('Publish step') {
      steps {
        echo 'Publishing '
      }
    }

  }
  environment {
    myname = 'Ronan'
  }
}