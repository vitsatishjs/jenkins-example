pipeline {
    agent any
    stages {
        stage('myStage'){
            steps {
                bat 'echo "hello myStage"'
                bat 'dir' 
            }
        }
        stage('Build') {
            steps { 
                bat 'echo "hello build"'
                bat 'dir' 
            }
        }
    }
}
