pipeline {
  agent any
  stages {
    stage('first stage') {
      steps {
        node(label: 'label')
        sh 'echo "hello world"'
      }
    }

  }
}