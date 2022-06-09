#!groovy
pipeline{
    agent none
    stages ('Docker Build'){
        agent any
        steps {
            sh 'docker build -t nkduy/simple-app'
        }
    }
}
