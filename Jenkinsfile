pipeline {
    agent { docker { image 'maven:3.8.4-openjdk-11-slim' } }
    stages {
        stage('build') {
            steps {
                echo 'building project...'
                sh 'mvn compile'
                sh 'mvn package'
                sh 'mvn test'
            }
        }
    }
}
