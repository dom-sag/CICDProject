pipeline {
    agent any

    stages {
        stage ('Git checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/dom-sag/CICDProject.git'
            }
        }

	stage ('Build') {
	steps {
	bat 'echo building on windows'
    }
}

}

}
