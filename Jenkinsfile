pipeline {
    agent { any { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello, World!"'
                sh '''
                    echo "Multi-line shell step. Standby for results of list(ls) utility..."
                    ls -lah
                '''
            }
        }
    }
}
