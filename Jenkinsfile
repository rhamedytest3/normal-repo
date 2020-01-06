pipeline {
    agent any
    stages {
        stage('maven:3.6.3-jdk-8') {
            agent {
                docker { image 'maven:3.6.3-jdk-8' }
            }
            steps {
                sh 'mvn --version'
            }
        }
    }
}
