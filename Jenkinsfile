pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh './gradlew'
            }
        }
    }
    post {
        always {
            junit 'build/reports/**/*.xml'
        }
    }
}
