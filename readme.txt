pipeline {
    agent any

    stages {
        stage('Testing') {
            steps {
                echo 'Testing pipeline SCM'
            }
        }
    }
}
