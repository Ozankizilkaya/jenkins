pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                echo 'Clone repo!'
                sh 'rm -rf docker'
                sh 'git clone https://github.com/Ozankizilkaya/jenkins.git'
            }
        }
        stage('run py') {
            steps {
                sh 'python3 hello_jenkins.py'
            }
        }
    }
}