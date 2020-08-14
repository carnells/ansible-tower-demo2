pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('Starting') {
      steps {
        echo 'This going to build the docker container to to be used by the project.'
      }
    }

  }
}