pipeline {
    agent any
    stages {
        stage('myStage2'){
            steps{
                sh 'echo "Just testing!"'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
