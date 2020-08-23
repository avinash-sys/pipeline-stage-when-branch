pipeline {
    agent any
    stages {
        stage('Build code') {
            steps {
                echo 'build the source code'
            }
        }
        stage('validation') {
            steps {
                echo 'validating'
            }
        }
        stage('integration test') {
            steps {
                echo 'performing validation testing'
            }
        }
        stage('Scanning') {
            when {
                branch 'master'
            }
            steps {
                echo 'perform scanning when branch is master'
            }
        }
    }
}
