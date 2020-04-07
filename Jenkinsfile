def CONTAINER_NAME="jenkins-pipeline"
def CONTAINER_TAG="latest"
def DOCKER_HUB_USER="hakdogan"
def HTTP_PORT="8090"

node {

    stage('Initialize'){
        def dockerHome = tool 'LocalDOCKER'
        env.PATH = "${dockerHome}:${env.PATH}"
    }

    stage('Checkout') {
        checkout scm
    }



}
