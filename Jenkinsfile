pipeline {
    agent any
 
    stages {
        stage('Build') {
            steps {
                script {
                    // Assuming Dockerfile is in the root of your project
                    docker.build("test")
                }
            }
        }
    }
}
