pipeline {
    agent any
    stages {
        stage('First'){
            when {
                anyOf {
                    branch 'master'
                    branch 'develop'
                }
            }
            steps {
                sh "echo I\'m here"
            }
        }
    }
}