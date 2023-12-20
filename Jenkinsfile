@Library('roboshop') _

pipeline {
    agent any
    stages {
        stage('code') {
            steps {
                echo 'Hello World'
                script {
                          demo.info 'Starting'
                          demo.warning 'Nothing to do!'
                        }
            }
        }
    }
}