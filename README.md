# hello-maven
# hello-maven
pipeline {
    agent any

    stages {
        stage('Check') {
            steps {
                echo "Pipeline is running"
            }
        }
    }
}
