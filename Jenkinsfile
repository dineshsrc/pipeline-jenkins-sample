pipeline {
    agent {
        docker 'node'
    }
    stages {
       stage('Initialize'){
         def dockerHome = 'LocalDOCKER'
         sh "echo ${dockerHome}"
         env.PATH = "${dockerHome}:${env.PATH}"
       }
        stage("testing 123") {
            steps {
                sh 'node --version'
            }
        }
    }
}
