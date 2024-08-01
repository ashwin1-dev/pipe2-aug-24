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
			      }
                           }
                 }
   }
