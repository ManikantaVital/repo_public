pipeline {
    agent any

    stages {
        stage('git clone') {
            steps {
                git 'https://github.com/ManikantaVital/java-azure-project.git'
            }
        }
        stage('package') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}

