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
        stage('Example deploy to development branch') {
            when {
                branch 'development'
            }
            steps {
                echo 'welcome to develpoment branch'
            }
        }
        stage('Example deploy to stagging branch') {
            when {
                branch 'stagging'
            }
            steps {
                echo 'welcome to stagging branch.'
            }
        }
    }
}
