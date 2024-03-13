pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post{
        always{
            emailext body: 'jay', subject: 'thyyyy', to: 'ranbh@gmail.com'
        }
    }
}
