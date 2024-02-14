pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('helo1') {
            steps {
                echo 'Hello World'
            }
        }
        stage('helo2') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post{
        always{
            emailext body: 'gvhb', subject: 'v', to: 'ranadhruv019@gmail.com'
        }
    }
}

