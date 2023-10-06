pipeline {
    agent any
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello Worldggg'
            }
        }
        stage('Example Deploy') {
            when {
                branch 'production'
            }
            steps {
                echo 'Deploying'
            }
        }
    }
}
