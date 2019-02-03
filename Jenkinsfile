pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Software compile"
                    ls -lah
                '''
            }
        }
         stage('Test') {
             steps {
               sh 'echo "Test the software"'
             }
    }
         stage('Deploy') {
             steps {
               sh 'echo "Deploy the software"'
             }
    }

}
}
