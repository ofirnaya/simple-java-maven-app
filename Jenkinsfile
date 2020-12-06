pipeline {
  agent {
    docker {
      image 'maven:3-alpine'
    }

  }
  stages {
    stage('Build') {
      agent {
        docker {
          image 'maven:3-alpine'
        }

      }
      steps {
        sh 'mvn clean build'
      }
    }

  }
}