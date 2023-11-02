pipeline {
  agent any
  stages {
    stage('Stage 1') {
      parallel {
        stage('Stage 1') {
          steps {
            sh 'echo "this is the build of $BUILD_NUMEBR of demo $DEMO"'
          }
        }

        stage('Stage 2') {
          steps {
            sh 'echo "It is build pipeline"'
          }
        }

      }
    }

  }
}