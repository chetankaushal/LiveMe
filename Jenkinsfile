
import org.jenkinsci.plugins.workflow.steps.FlowInterruptedException

def fastlane(task) {
	sh "bundle exec Fastlane ${task}"
  }

node("master") {
	stage('Checkout') {
		deleteDir()
		checkout scm
	}
}
