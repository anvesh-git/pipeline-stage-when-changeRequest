pipeline {
    agent any
    stages {
        stage('building master bracnh') {
            when {
                changeRequest()
            }
            steps {
                echo 'building pull request'
            }
        }
    }
}
