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
                sh 'docker run -t -d --entrypoint='' -u 115:122 -u root -w /var/lib/jenkins/workspace/example -v /var/lib/jenkins/workspace/example:/var/lib/jenkins/workspace/example:rw,z -v /var/lib/jenkins/workspace/example@tmp:/var/lib/jenkins/workspace/example@tmp:rw,z -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** -e ******** docker:dind cat
'
                sh 'docker build -t tejasudarshan58/my-app-1.0-SNAPSHOT .'
            }
        }
        // Add more stages as needed
    }
    // Add post-build actions as needed
}
