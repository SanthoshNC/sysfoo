pipeline {
    agent any
    stages {
        stage('Step 1 Git clone') {
            steps {
                echo "Cloning the Git"
				sh "git --version"
            }
        }
		stage('Step 2 Maven Build') {
            steps {
                echo "Build Process"
				sh "mvn -version"
            }
        }
		stage('Step 3 Deploying the artifact') {
            steps {
                echo "Deploying artifact Process"
            }
        }
    }
}
