pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh '/home/ubuntu/jenkins/gradlew.sh'
            }
        }
    }
    post {
        always {
            junit '/home/ubuntu/jenkins/build/reports/**/*.xml'
        }
    }
}
