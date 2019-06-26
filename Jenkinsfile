
import org.jenkinsci.plugins.workflow.steps.FlowInterruptedException

node("checkout") {
	stage('Checkout') {
		deleteDir()
		checkout scm
	}
}

def fastlane(task) {
	sh "bundle exec Fastlane ${task}"
  }