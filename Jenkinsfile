pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                sh 'go version'
                sh 'ls -a'
                echo "Hello World from Jenkins"
            }
        }
    }
}



