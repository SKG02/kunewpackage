pipeline {
    agent any
    stages {
        stage("init") {
            steps {
                echo 'building'
                }
            }
        }
        stage("build testing") {
            steps {
                script {
                    echo 'testing'
                }
            }
        }
        stage("build image") {
            steps {
                script {
                    echo 'imaging'
                }
            }
        }
        stage("deploy") {
            steps {
                script {
                    echo 'deploying'
                }
            }
        }
    }   
}
