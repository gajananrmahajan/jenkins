pipeline {
    agent any
    tools {
        maven 'Maven 3.2.1'
        jdk 'jdk8'
    }
    stages {
        stage('Build') {
            steps {
                echo "Building"
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