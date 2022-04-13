pipeline {
    agent any
    stages {
        stage('checkout') {
            steps {
            git branch: 'master',
            url: 'https://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@github.com/rya1992/CodingLand.git'
            }
        }
        stage('build') {
            steps {
                echo 'testing the application....'
                docker {
                    image 'gradle:6.7-jdk11'
                    // Run the container on the node specified at the top-level of the Pipeline, in the same workspace, rather than on a new node entirely:
                }
            }
        }
        stage('test') {
            steps {
                echo 'testing the application....'
            }
        }
        stage('deploy') {
            steps {
                echo 'deplying the application....'
            }
        }

    }
}
