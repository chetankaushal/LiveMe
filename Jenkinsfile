

node("checkout") {
	stage('Checkout') {
		deleteDir()
		checkout scm
	}

def fastlane(task) {
	sh "bundle exec Fastlane ${task}"
  }