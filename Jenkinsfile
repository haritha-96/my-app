pipeline {
    agent any
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Example deploy to development branch') {
            when {
                branch 'developmemt'
            }
            steps {
                echo 'welcome to development branch.'
            }
        }
    }
}
