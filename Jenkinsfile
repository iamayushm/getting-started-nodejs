// Jenkinsfile (Declarative Pipeline)
/* Requires the Docker Pipeline plugin */
pipeline {
    agent { dockerfile true }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}
