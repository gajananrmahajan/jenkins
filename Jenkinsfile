pipeline {
    agent any
    tools {
        maven 'Maven 3.2.1'
        jdk 'jdk8'
    }
    stages {

        stage('Intialize') {
                    steps {
                        bat '''
                            echo "PATH = ${PATH}"
                            echo "JAVA_HOME = ${JAVA_HOME}"
                            echo "M2_HOME = ${M2_HOME}"
                        '''
                    }
                }

        stage('Build') {
            steps {
                echo "Building"
                bat 'mvn clean install'
            }
        }

        stage('Deploying') {
                    steps {
                        echo "Deploying"
                }
        }

        stage('Testing') {
                            steps {
                                echo "Testing"
                        }
                }
    }
}