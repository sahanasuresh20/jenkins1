pipeline {
    agent any
options {
  disableConcurrentBuilds()
}
    stages {
        stage('b') {
            steps {
                echo 'Hello World hyy'
            }
        }
        stage('t') {
            steps {
                echo 'Hello World good morning'
            }
        }
        stage('d') {
            input {
  message 'welcome sahana'
            }
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
