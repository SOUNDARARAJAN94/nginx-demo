pipeline { 
    agent any

    stages {

        stage('Clone') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/SOUNDARARAJAN94/nginx-demo.git'
            }
        }

        stage('Deploy') {
            steps {
                sh '''
                sudo cp index.html /usr/share/nginx/html/
                '''
            }
        }

    }
}
