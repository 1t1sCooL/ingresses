pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
                script {
                    sh "kubectl apply -f ingress.yaml"
                }
            }
        }
    }
}