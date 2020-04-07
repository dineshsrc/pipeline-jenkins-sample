pipeline {
    agent {
        docker{
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
