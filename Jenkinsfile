pipeline {
    agent { docker { image 'maven:3.6.3-adoptopenjdk-8' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn install'
            }
        }
    }
}
