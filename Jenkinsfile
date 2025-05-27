pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Checkout SCM github') {
            steps {
                deleteDir()
                git branch: 'main', credentialsId: 'user-github', url: 'https://github.com/KevGithubb/depotgithub.git'
            }
        }
        
    }
}
