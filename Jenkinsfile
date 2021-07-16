pipeline {
    agent any

    stages {
        stage('Code') {
            steps {
                echo 'Code created'
            }
        }
                stage('git') {
            steps {
                echo 'Uploaded in GIT repo'
            }
        }
                stage('test') {
            steps {
                echo 'Test using test tools'
            }
        }
    }
    post {
        success {
            echo "Perform sucess action"
        }
    }
}
