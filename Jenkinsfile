pipeline {
    agent any
    tools {
        maven 'M2_HOME'
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'mvn clean'
                sh 'mvn install'
                sh 'mvn package'
            }
        }
        
        stage('build') {
            steps {
                echo 'Hello build'
            }
        }
        
        stage('deploy') {
            steps {
                echo 'Hello deploy'
                sleep 3
            }
        }
        
        stage('test') {
            steps {
                echo 'Hello test'
                sleep 3
            }
        }
        
    }
}
