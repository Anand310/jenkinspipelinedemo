pipeline {
    agent any

    stages {
        stage('integrate new changes') {
            steps {
                echo 'integrating new chnges'
            }
        }
        stage('Build') {
            steps {
                echo 'Building'
            }
        }
        stage('test') {
            steps {
                echo 'testing the files'
            }
        }
        stage('deploy') {
            steps {
                echo 'Deploying'
            }
        }
    }
}
