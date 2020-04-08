pipeline {
    agent {
        docker{
         image 'maven:3.3.3'
         args '-v $HOME:/root'
        }
    }
    stages {
        stage("Build") {
            steps {
                dir(path: '/root') {
                sh 'mvn -B'
                }
            }
        }
    }
}
