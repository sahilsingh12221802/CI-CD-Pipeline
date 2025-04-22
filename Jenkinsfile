pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "✅ Just a simple build stage running"
                sh 'cat file.txt'
            }
        }

        stage('Done') {
            steps {
                echo "🎉 building process done"
            }
        }
    }
}