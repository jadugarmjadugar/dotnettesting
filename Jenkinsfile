pipeline {
    agent any
    stages {
        stage("init") {
            steps {
                script {
                    echo "building jar1"
                }
            }
        }
        stage("build jar") {
            steps {
                script {
                    echo "building jar2"
                    //gv.buildJar()
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
                    echo "deploying"
                    //gv.deployApp()
                }
            }
        }
    }   
}
