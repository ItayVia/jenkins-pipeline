pipeline {
    agent any
    tools {
        go '1.19'
    }
    stages {
        stage ('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Run') {
            steps {
                sh 'go run main.go'
            }
        }

    }
}