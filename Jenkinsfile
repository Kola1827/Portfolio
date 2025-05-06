pipeline {
    agent any

    tools {
        nodejs 'nodejs_18_20_8' // Match the name you gave in Global Tool Config
    }

    stages {
        stage('Install') {
            steps {
                bat 'npm install'
            }
        }

        stage('Build') {
    steps {
        bat 'set "CI=" && npm run build'
    		}
	}

    }
}
