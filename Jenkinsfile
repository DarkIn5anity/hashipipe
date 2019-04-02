pipeline {
    agent {
        docker { image 'darkinsanity/hasipipe' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'packer --version'
            }
        }
    }
}
