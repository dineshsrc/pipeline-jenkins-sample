pipeline {
    agent {
        docker 'node'
    }
    stages {
       stage('Initialize'){
         def dockerHome = tool 'LocalDOCKER'
         env.PATH = "${dockerHome}:${env.PATH}"
       }
        stage("testing 123") {
            steps {
                sh 'node --version'
            }
        }
    }
}
