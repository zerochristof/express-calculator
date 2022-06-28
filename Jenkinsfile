
pipeline {
	agent any

		stages {
			stage('build'){
				steps {
					sh 'npm install'
				}
			}
			stage('unit-tests') {
				steps {
					sh 'npm run unit-test'
				}
				when {
				anyOf {
				branch 'develop'
				branch 'feature/*'
				}
				}
			}
			stage('integration-tests') 
				{
				when {
				anyOf {
				branch 'develop'
				}
				steps {
					sh 'npm run integration-test'
				}

			}

		
		}
}
