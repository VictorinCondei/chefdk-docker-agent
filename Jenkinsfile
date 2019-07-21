pipeline {
    agent { docker { image 'chef/chefdk' } }
    stages {
        stage('build') {
            steps {
                sh 'chef --version'
            }
        }
    }
}
