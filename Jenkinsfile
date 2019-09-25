pipeline {
    agent any
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Example deploy to master branch') {
            when {
                branch 'feature'
            }
            steps {
                echo 'welcome to master branch.'
            }
        }
    }
}
