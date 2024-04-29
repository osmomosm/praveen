pipeline {
    agent any
    stages {
        stage("Git Checkout"){
            steps{
                git branch: 'main', credentialsId: '74c8327f-01f3-49f3-b401-660ce437884f', url: 'https://github.com/osmomosm/praveen.git'
            }
        }
    }
}
