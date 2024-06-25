pipeline {
    agent any
    
    stages {
        stage('Code') {
            steps {
                echo "This is Code stage"
                git url: 'https://github.com/subha152/newSpringbootCICD.git', branch: "main"
            }
        }
        
        stage('Build') {
            steps {
                echo "This is Build stage"
            }
        }
        
        stage('Deploy') {
            steps {
                echo "This is Deploy stage"
            }
        }
    }
}

