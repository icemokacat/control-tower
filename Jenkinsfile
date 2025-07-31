pipeline {
	agent any
	stages {
		stage('Pull OK') {
			steps {
				echo 'Success Webhook from Github to Jenkins'
			}
		}
		stage('Archive Artifacts') {
			steps {
				archiveArtifacts artifacts: 'controll-view/**', fingerprint: true
			}
		}
	}
}