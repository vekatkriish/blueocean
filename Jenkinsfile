pipeline {
  agent {
    docker {
      image 'alpine'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh 'myscript.sh'
      }
    }
  }
}