pipeline {
    agent any
    stages {
        stage("init") {
            steps {
                script {
                    echo "building jar1"
                    sh 'dotnet clean .'
                }
            }
        }
        stage("build jar") {
            steps {
                script {
                    echo "building jar2"
                    sh 'dotnet build .
                }
            }
        }
        stage("build image") {
            steps {
                script {
                    echo "building image"
                    //gv.buildImage()
                }
            }
        }
        stage("deploy") {
            steps {
                script {
                    echo "deploying test"
                    //gv.deployApp()
                }
            }
        }
    }   
}
