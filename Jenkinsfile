pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        parallel(
          "error": {
            echo 'yo '
            
          },
          "t2": {
            bat(script: 'echo "sup"', returnStatus: true)
            
          }
        )
      }
    }
  }
}