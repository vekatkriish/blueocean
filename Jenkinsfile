pipeline {
  agent {
    docker {
      image 'alpine'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh 'sh "myscript.sh"'
      }
    }
  }
}