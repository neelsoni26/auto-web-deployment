pipeline{
	agent any

	stages {
		stage('Building') {
			steps {
				echo 'The code will be now build artifact'
			}
		}
		stage('artifact archiving') {
			steps {
				echo 'The code will be now uploaded on artifact repo'
			}
		}
		stage('Testing') {
			steps {
				echo 'now testing'
			}
		}
		stage('stageing') {
			steps {
				echo 'now steging'
			}
		}
		stage('Deploy') {
			steps {
				echo 'now deploy'
			}
		}
	}
}
