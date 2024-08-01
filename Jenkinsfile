pipeline {
	agent any

	tools {
		maven "jenkin-maven"
  	     }


	stages {
		stage('build') {
			steps {
				git 'https://github.com/ashwin1-dev/war-file-12dec23.git'
			        sh 'mvn clean package'
				sh 'scp target/mob6-1.0.jar   192.168.10.32:/opt/apache-tomcat-9.0.91/webapps'
			      }
                           }
                 }
   }
