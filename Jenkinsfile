pipeline {
  agent {
    node {
      label 'javaapp'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        build 'Hello'
      }
    }
    stage('deploy') {
      steps {
        writeFile(file: 'hellomiracle', text: 'demo')
      }
    }
  }
}