pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'docker build -f ./Centos-ruby2/Dockerfile'
            }
        }
    }
}
