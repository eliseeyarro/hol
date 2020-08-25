pipeline {
    agent any
    tools {
        maven 'M2_HOME'
    }

    stages {
        
        stage('build') {
            steps {
                echo 'Hello build'
                sh 'mvn clean'
                sh 'mvn install'
                sh 'mvn package'
            }
        }
        
        stage('test') {
            steps {
                echo 'Hello test'
                sleep 3
            }
        }
        
        stage('deploy') {
            steps {
                echo 'Hello deploy'
                sleep 3
            }
        }
        
    }
}
