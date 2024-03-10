pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello World!"'
            }
        }
    }
    post {
        always {
            echo 'This will always run'
        }
        success {
            echo 'Success!'
        }
        failure {
            echo 'Failed :('
        }
        changed {
            echo 'Something changed...'
        }
    }
}
