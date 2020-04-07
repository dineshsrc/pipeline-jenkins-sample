pipeline {
    agent {
        docker 'node'
    }
    stages {
       stage('Initialize'){
         def dockerHome = tool 'myDocker'
         env.PATH = "${LocalDOCKER}:${env.PATH}"
       }
        stage("testing 123") {
            steps {
                sh 'node --version'
            }
        }
    }
}
