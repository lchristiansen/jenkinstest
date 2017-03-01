pipeline {
    agent { docker 'php' }
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello Team"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}


