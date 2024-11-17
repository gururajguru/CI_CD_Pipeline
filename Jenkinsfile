pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Checkout the repository
                git 'https://github.com/gururajguru/CI_CD_Pipeline.git'
            }
        }
        stage('Build') {
            steps {
                // Build step
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                // Test step
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                // Deploy step
                echo 'Deploying...'
            }
        }
    }
}
