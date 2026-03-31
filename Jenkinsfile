pipeline {
    agent any
    stages {
        stage('Clean Workspace') {
            steps {
                cleanWs()
            }
        }
        stage('Clone Repository') {
            steps {
                sh 'pipeline {
    agent any

    stages {

        stage('Clean Workspace') {
            steps {
                cleanWs()
            }
        }

        stage('Clone Repository') {
            steps {
                  git branch:'main', url: 'https://github.com/Elvi-2202/depotOnlinedev26.git'
            }
        }

    }
}'
            }
        }

    }
}