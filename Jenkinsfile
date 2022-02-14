pipeline {
    agent node {
        customWorkspace '/learn'
    }
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello world"'
            }
        }
    }
}