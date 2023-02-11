pipeline {
	agent any

	stages {
		stage('docker run') {
			steps {
		    	script {
		    	sh "sudo docker run -d --name web -p 80:80 caosbinario/homer_page:1.0.0-9"	
				}
			}
		}
	}
}
