//Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any
    tools{
        maven 'Maven'
    }
    stages {
        stage('build') {
            steps {
                echo 'Hi stage1'
                bat "mvn clean install"
                echo 'Hi stage1 completed'
            }
        }
        stage('test') {
            steps {
                echo 'Hi stage2'
            }
        }
    }
}