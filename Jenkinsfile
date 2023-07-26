pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World12112" > /tmp/test10000044444.txt'
                sh 'mkdir /tmp/test'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}

