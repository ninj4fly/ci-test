pipeline {
    agent { node { label 'pena' } }

    stages {
        stage('Test') {
            steps {
                sh './run_test.sh'
            }
        }
    }
}
