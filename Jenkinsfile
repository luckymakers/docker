pipeline {
    
    agent { 
        dockerfile {label 'master'}
    }
     
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}
