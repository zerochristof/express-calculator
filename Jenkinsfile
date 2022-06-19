 stage('Initialize'){
        def dockerHome = tool 'docker1'
        env.PATH = "${dockerHome}/bin:${env.PATH}"
    }




pipeline {
	agent{
		docker { image 'node:14-alpine' }
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
}
