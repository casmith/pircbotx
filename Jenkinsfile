pipeline {
    agent {
      docker {
        image 'maven:3.6.3-adoptopenjdk-8'
        args '-v $HOME/.m2:/var/lib/jenkins/workspace/pircbotx_modernize/?/.m2'
      }
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn install'
            }
        }
    }
}
