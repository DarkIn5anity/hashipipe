pipeline {
    agent {
        docker { image 'darkinsanity/hashipipe' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'packer --version'
            }
        }
    }
}
