pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                script {
                    docker.build("adservice:1.0.0")
                }
            }
        }
    }
}
