pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shel steps works too"
                    ls -lah
                '''
            }
        }
    }
}