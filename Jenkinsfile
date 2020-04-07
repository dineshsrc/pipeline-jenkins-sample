pipeline {
    agent {
        docker 'node'
    }
     environment {
        PATH = 'C:/Program Files/Docker Toolbox'
    }
    stages {
        stage("testing 123") {
            steps {
                sh "env PATH=$PATH:\$PATH"
                sh 'node --version'
            }
        }
    }
}
