pipeline {
    agent any

    stages {
        stage('b') {
            steps {
                echo 'Hello World hyy'
            }
        }
        stage('t') {
            steps {
                echo 'Hello World'
            }
        }
        stage('d') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post
    {
        always
        {
            emailext body: 'dfshjsf', subject: 'shgjd', to: 'sahanasahu848@gmail.com'
        }
    }
}
