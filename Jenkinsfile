pipeline {
  agent none
  stages {
    stage('Crucible') {
		agent {
			docker { image 'crucible' }
		}
		steps {
			echo 'crucible'
		}
    }
	stage('sonarqube') {
		agent {
			docker { image 'sonarqube' }
		}
		steps {
			echo 'sonarqube'
		}
    }
	stage('Unit Tests') {
		agent {
			docker { image 'unitTest' }
		}
		steps {
			echo 'Unit Tests'
		}
    }
	stage('Security Test') {
		agent {
			docker { image 'securityTest' }
		}
		steps {
			echo 'Security Test'
		}
    }
	stage('Visual Regression') {
		agent {
			docker { image 'visualRegression' }
		}
		steps {
			echo 'Visual Regression'
		}
    }
	stage('Integration Test') {
		agent {
			docker { image 'integrationTest' }
		}
		steps {
			echo 'Integration Test'
		}
    }
  }
}
