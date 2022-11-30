pipeline {
    agent any
    stages {
        stage('download') {
            steps {
                sh '''
                ls
                echo "hola a todos"
                '''
            }
        }
        stage('compilar') {
            steps {
                sh '''
                pwd
                echo "hello world"
                '''
            }
        }
        stage('deployar') {
            steps {
                sh '''
                echo "Salut"
                '''
            }
        }
    }
}
