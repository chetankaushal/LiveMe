
import org.jenkinsci.plugins.workflow.steps.FlowInterruptedException

def fastlane(task) {
	sh "bundle exec fastlane ${task}"
  }


	stage('Build and Test') {
		fastlane 'test'
	}
