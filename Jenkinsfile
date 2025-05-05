pipeline {
    agent any
        stages {
            stage('Checkout GIT') {
                steps {
                    echo ' Pulling...'
                        git branch: 'main',
                        url : 'https://github.com/Ghassen2001/atelier_git.git'
                }
            }
        }
}
