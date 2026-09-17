pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git branch: 'main', url: 'https://github.com/HeyItsArsh/Agile-Lab-7-2.git'
      }
    }
    stage('Show Parameter') {
      steps {
        echo "Selected Environment: ${params.ENVIRONMENT}"
      }
    }
    stage('Build for Environment') {
      steps {
        echo "Building the Application for the ${params.ENVIRONMENT} Environment..."
      }
    }
  }
}
