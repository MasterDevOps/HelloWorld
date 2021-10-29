pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Start..'
                sh 'mvn -B -DskipTests clean package'
                echo 'Building End'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
