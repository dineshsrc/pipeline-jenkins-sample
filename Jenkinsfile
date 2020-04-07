pipeline {
    agent {
        docker{
         image "digitizedpost/dockerjenkinsdemorepo:5"
         args '-v $HOME:C:/Program Files/Docker Toolbox'
        }
    }
    stages {
        stage("testing 123") {
            steps {
                dir(path: 'C:/Program Files/Docker Toolbox') {
                sh 'ls -l'
                }
            }
        }
    }
}
