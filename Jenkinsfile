pipeline {
  agent any
  stages {
    stage('Prvy') {
      parallel {
        stage('Prvy') {
          steps {
            echo 'Prve ahoj'
          }
        }

        stage('PPrvy') {
          steps {
            echo 'paralel v prvom ahoj'
            sh 'echo "skuska"'
          }
        }

      }
    }

    stage('Druhy') {
      steps {
        echo 'Druhy'
      }
    }

  }
}