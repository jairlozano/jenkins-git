pipeline {
    agent {
      docker { image 'ubuntu:18.04'}
      label 'docker-slave'
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo Hola'
            }
        }
    }
}
