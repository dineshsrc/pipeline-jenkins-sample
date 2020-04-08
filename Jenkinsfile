pipeline {
    agent {
        docker{
         image 'digitizedpost/dockerjenkinsdemorepo:5'
         args '-v tcp://192.168.99.100:2376'
        }
    }
    stages {
        stage("testing 123") {
            environment {
                HOME = '.'
            }
            steps {
                dir(path: 'C:/Program Files/Docker Toolbox') {
                sh 'ls -l'
                }
            }
        }
    }
}
