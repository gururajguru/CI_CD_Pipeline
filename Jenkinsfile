pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/gururajguru/CI_CD_Pipeline.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
