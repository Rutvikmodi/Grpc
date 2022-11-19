Jenkinsfile (Declarative Pipeline)
/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Hi stage1'
            }
        }
        stage('test') {
            steps {
                echo 'Hi stage2'
            }
        }
    }
}