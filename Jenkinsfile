pipeline {
	agent any
	stages {
		stage ('Build Backend') {
			step {
				sh 'mvn clean package -DskipTests=true'
			}
		}
	}
}