pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Get some code from a GitHub repository
                sh "git clone git@github.com:sacdev214/Jenkins-Test-1.git"
                // Run Maven on a Unix agent.
            }
        }
        stage("Build") {
            steps {
                sh "mvn clean compile install"
            }
        }
    }
            }
