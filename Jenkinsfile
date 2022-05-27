pipeline {
  agent linux 
  stages {
    stage('Gradle Build') {
      steps {
		echo "build statge"
      }
    }
    
  }
  post {
    always {
      echo "post statge"
    }
  }
}
