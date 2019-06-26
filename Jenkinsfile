
import org.jenkinsci.plugins.workflow.steps.FlowInterruptedException

def fastlane(task) {
	sh "bundle exec fastlane ${task}"
  }

withRubyBootStrap {
	stage('Build and Test') {
		fastlane 'test'
	}
}