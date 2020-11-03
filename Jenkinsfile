pipeline {
  agent none
  stages {
    stage('code review') {
      steps {
        echo 'code review'
      }
    }

    stage('sonarqube') {
      steps {
        echo 'sonarqube'
      }
    }

    stage('Unit Tests') {
      steps {
        echo 'unit test'
      }
    }

    stage('Security Test') {
      steps {
        echo 'security test'
      }
    }

    stage('Visual Regression') {
      steps {
        echo 'Visual regression'
      }
    }

    stage('Integration') {
      steps {
        echo 'integration test'
      }
    }

  }
}