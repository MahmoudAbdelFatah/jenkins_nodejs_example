pipeline {
    agent any

    stages {
        stage('test') {
            steps {
                echo 'testing the application...'
            }
        }
        stage('build image') {
            when {
                expression {
                    BRANCH_NAME == 'master'
                }
            }
            steps {
                echo 'Building the application...'
            }
        }
        stage('deploy image') {
            when {
                expression {
                    BRANCH_NAME == 'master'
                }
            }
            steps {
                echo 'Building the application...'
            }
        }
        
    }
}
