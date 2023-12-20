pipeline {
    agent {
        docker {
            image 'docker:dind'
            args '-u root'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'docker build -t tejasudarshan58/my-app-1.0-SNAPSHOT .'
            }
        }
        // Add more stages as needed
    }
    // Add post-build actions as needed
}
