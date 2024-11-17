pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm: [
                    $class: 'GitSCM', 
                    branches: [[name: '*/main']], 
                    userRemoteConfigs: [[url: 'https://github.com/gururajguru/CI_CD_Pipeline.git']]
                ]
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
    }
}
