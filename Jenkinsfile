pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'docker build -f ./centos-ruby2/Dockerfile'
            }
        }
    }
}
