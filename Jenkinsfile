pipeline {
  agent {
    docker {image 'node:16-alpine'}
  }
  stages {
    stage("rpm build") {
      steps {
        echo "building the application...."
        sh 'node --version'
      }
    }
  }
}
