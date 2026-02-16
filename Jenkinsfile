pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git https://github.com/manikumarat3-blip/frontend-jenkins-app.git

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
