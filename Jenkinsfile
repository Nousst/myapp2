pipeline {
    agent any

    stages {
        stage('initialaise') {
            steps {
                sh 'terraform init'
            }
        }
        stage('format the code') {
            steps {
                sh 'terraform validate'
            }
        }
         stage('validate') {
            steps {
                echo 'terraform validate'
            }
        }
         stage('plan') {
            steps {
                echo 'terraform plan'
            }
         }
    }
             
}
