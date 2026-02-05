pipeline {
    agent any
    stages {
        stage('Fetch from Git') {
            steps {
                echo 'Successfully pulled Jenkinsfile from GitHub!'
            }
        }
        stage('Automated Build') {
            steps {
                echo 'Running build steps from SCM...'
            }
        }
    }
}
