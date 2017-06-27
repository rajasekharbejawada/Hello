pipeline {
  agent none
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