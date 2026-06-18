pipeline {
    agent any

    stages {

        stage('Deploy') {
            steps {
                sh '''
                sudo cp index.html /usr/share/nginx/html/
                sudo cp style.css /usr/share/nginx/html/
                '''
            }
        }

    }
}
