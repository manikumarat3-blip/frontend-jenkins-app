pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/your-username/simple-html-jenkins.git'
            }
        }

        stage('Deploy') {
            steps {
                sh '''
                sudo cp index.html /var/www/html/
                '''
            }
        }
    }
}
