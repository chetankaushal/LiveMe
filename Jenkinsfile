pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        checkout scm
      }
    }
  }

def fastlane(task) {
	sh "bundle exec Fastlane ${task}"
  }

}