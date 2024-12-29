pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                checkout scm
            }
        }
        stage('Execute Bash Script') {
            steps {
                sh 'chmod +x script.sh && ./script.sh'
            }
        }
    }
}
