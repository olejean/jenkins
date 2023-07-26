pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World12112"' > /tmp/test100000.txt
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}

