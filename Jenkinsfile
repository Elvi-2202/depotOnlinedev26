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
                sh 'git clone https://github.com/Elvi-2202/depotOnlinedev26.git'
            }
        }

    }
}