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
                branch 'master'
            }
            steps {

                echo 'welcome to master branch'

            }
        }
    }
}
