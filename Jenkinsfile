pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello all Worlds"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
