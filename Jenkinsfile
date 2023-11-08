pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                script {
                    sh 'python helloworld.py'
                }
            }
        }
    }
    
    post {
        always {
            echo 'Hello World!'
        }
    }
}
