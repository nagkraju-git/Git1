pipeline {
  agent any
  stages {
    stage('local') {
      steps {
        ws(dir: '/Users/nagkraju/Git1') {
          echo 'Hello!'
        }
        
      }
    }
  }
  environment {
    Server = 'local'
  }
}