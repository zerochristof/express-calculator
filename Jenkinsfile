
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
			}
			stage('integration-tests') {
				steps {
					sh 'npm run intergration-test'
				}

			}
		
i		}
}
