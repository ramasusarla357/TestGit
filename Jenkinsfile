pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        parallel(
          "Dev": {
            echo 'Dev'
            
          },
          "Scan": {
            echo 'sacn'
            
          },
          "UT": {
            echo 'UT'
            
          }
        )
      }
    }
    stage('Test') {
      steps {
        echo 'Test'
      }
    }
    stage('Deploy') {
      steps {
        echo 'deploy'
      }
    }
  }
}