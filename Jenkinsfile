pipeline {
    agent { label 'linux-vm' }
    stages {
        stage('Check Agent') {
            steps {
                echo "Running on agent: ${env.NODE_NAME}"
                sh 'uname -a'
            }
        }
    }
}