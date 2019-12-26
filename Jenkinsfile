node {
    /* Requires the Docker Pipeline plugin to be installed */
    sudo docker.image('node:7-alpine').inside {
        stage('Test') {
            sh 'node --version'
        }
    }
}
