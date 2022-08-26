pipeline {
    agent { docker { image 'maven:3.8.4-openjdk-11-slim' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                echo 'building project...'
                sh 'mvn compile'
                sh 'mvn package'
            }
        }
    }
}
