pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "The software needs to be compiled first"
                    ls -lah
                '''
            }
        }
    
        stage('Test') {
            steps {
                sh 'echo "OK, all is good in building this software"; exit 0'
            }
        } 
        stage('Deploy') {
            steps {
                sh 'echo "Now run the script to deploy this into AWS"'
            }
    }
}
