pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'building project...'
                sh 'mvn compile'
                sh 'mvn package'
            }
        }
    }
}
