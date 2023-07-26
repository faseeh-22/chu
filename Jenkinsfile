pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                git credentialsId: 'git-checkout-branch-pipeline', url: 'https://github.com/faseeh-22/chu.git'
            }
        }
    }
}

