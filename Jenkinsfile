node{
	
	stage('scm'){
          checkout scm
	}
	
	
	stage('Docker Build Image') {
		def customImage = docker.build("${env.JOB_NAME.}:v1.${env.BUILD_ID}")
       }
	 
}
