pipeline {
    agent {
        docker{
         image 'digitizedpost/dockerjenkinsdemorepo:5'
         args '-v $HOME:/root'
        }
    }
    stages {
        stage("testing 123") {
            environment {
                HOME = '.'
            }
            steps {
                dir(path: '/root') {
                sh 'ls -l'
                }
            }
        }
    }
}
