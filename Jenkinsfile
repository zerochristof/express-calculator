pipeline {
	agent{
		docker { image 'node;14-apline' }
	}
}
stages {
	stage('Build'){
		steps {
			echo ' Buildning'
				sh 'node --version'
		}
	}
	stage('Test') {
		steps {
			echo 'Testing' 
				sh 'node --version'
		}
	}
	stage('Deplot'){
		steps {
			echo 'Deploy'
				sh 'node --version'
		}
	}

}
