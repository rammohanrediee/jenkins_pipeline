pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/rammohanrediee/jenkins_pipeline.git'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying index.html...'
                sh 'mkdir -p /tmp/website'
                sh 'cp index.html /tmp/website/'
            }
        }
    }
}
