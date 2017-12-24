pipeline {
    agent { docker 'php' }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
                sh 'echo "THIS IS ONLY A TEST"'
                sh 'php artisan'
            }
        }
    }
}