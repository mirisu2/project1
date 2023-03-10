pipeline {
    agent {
        label 'linux'
    }
    stages {
        stage('test trigger') {
            agent {
                label 'linux'
            }
            steps {
                sh 'hostname'
                sh 'env | sort'
            }
        }
    }
}
