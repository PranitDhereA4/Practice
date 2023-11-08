pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                script {
                    sh 'python hello_world.py'
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
