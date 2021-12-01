pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Building'
          }
        }

        stage('Parrel Build') {
          steps {
            echo 'parrel build'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'testing stage'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }

  }
}