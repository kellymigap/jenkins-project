pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        checkout scm
      }
    }

    stage('Build') {
      steps {
        echo "Build step here"
        // Example:
        // sh 'npm ci && npm test'
        // sh 'mvn -v'
      }
    }

    stage('Test') {
      steps {
        echo "Test step here"
      }
    }
  }

  post {
    always {
      echo "Pipeline finished."
    }
  }
}
