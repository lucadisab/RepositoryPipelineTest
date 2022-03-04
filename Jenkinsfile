pipeline {
  agent {
    node {
      label 'Esegue la pipe'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Stage \'build\''
      }
    }

    stage('Test') {
      steps {
        echo 'Stage \'test\''
      }
    }

    stage('Deploy') {
      steps {
        echo 'Stage \'deploy\''
      }
    }

  }
}