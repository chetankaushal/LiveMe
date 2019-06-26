
import org.jenkinsci.plugins.workflow.steps.FlowInterruptedException

def fastlane(task) {
	sh "bundle exec Fastlane ${task}"
  }

node("xcode_stable") {
	stage('Checkout') {
		deleteDir()
		checkout scm
	}
}
