pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh ""
                sh "git clone https://github.com/Addalin-CP3445/testing.git"
                echo 'Building..'
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
}
