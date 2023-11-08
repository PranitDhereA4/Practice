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
    stages {
        stage('Trigger') {
            steps {
                sh 'echo "Jenkins build triggered by MS Teams webhook"'
            }
        }
    }
    post {
        always {
            echo 'Hello World!'
        }
    }

    
}
