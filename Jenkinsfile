pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo "Building Simple HTML App"
            }
        }

        stage('Deploy') {
            steps {
                sh '''
                cp -r * /usr/share/nginx/html/
                '''
            }
        }
    }
}
