pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'mvn clean'
            }
        }
        stage('build') {
            steps {
                sh 'mvn validate'
            }
        }
         stage('build') {
            steps {
                sh 'mvn compile'
            }
        }
        stage('build') {
            steps {
                sh 'mvn test -DskipTests'
            }
        }
        stage('build') {
            steps {
                sh 'mvn package -DskipTests'
            }
        }
        stage('build') {
            steps {
                sh 'mvn verify -DskipTests'
            }
        }
         stage('build') {
            steps {
                sh 'mvn install -DskipTests'
            }
        }
    }
}
