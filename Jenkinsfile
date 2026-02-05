pipeline {
    agent any
    stages {
        stage('Fetch from Git') {
            steps {
                echo 'Proof: This stage is running from the GitHub Jenkinsfile!'
            }
        }
        stage('Automated Build') {
            steps {
                echo 'Building the project...'
            }
        }
    }
    post { 
        success { 
            echo 'SUCCESS: The build finished perfectly!' 
        }
        failure { 
            echo 'FAILURE: Something went wrong in the pipeline.' 
        }
    }
}
