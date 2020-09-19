pipeline {
    agent any
    stages {
        stage('building master bracnh') {
            when {
                changeRequest title:"when-pr"
            }
            steps {
                echo 'building pull request by title'
            }
        }
    }
}
