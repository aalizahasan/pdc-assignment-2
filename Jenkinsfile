pipeline {
    agent any
    triggers { githubPush() }
    stages {
        stage('Build') { steps { echo 'PDC Assignment 2: CI build' } }
        stage('Test') { steps { sh 'test -f README.md' } }
    }
}
