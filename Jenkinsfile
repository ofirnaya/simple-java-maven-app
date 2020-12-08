pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn clean package'
      }
    }

    stage('Print') {
      steps {
        echo 'Finished'
      }
    }

  }
}