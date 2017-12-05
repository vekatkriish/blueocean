pipeline {
  agent {
    docker {
      image 'alpine'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh '''sh "chmod +x  ./myscript.sh"


sh "./myscript.sh"
'''
      }
    }
  }
}