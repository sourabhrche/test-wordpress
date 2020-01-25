pipeline {
  agent none
  stages {
    stage('test') {
      steps {
        build 'test'
      }
    }

  }
  environment {
    build = 'assets'
  }
}