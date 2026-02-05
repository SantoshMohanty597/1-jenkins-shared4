@Library('my-shared-lib') _

pipeline {
    agent any
    stages {
        stage('Test Shared Lib') {
            steps {
                hello()
                echo "This is the test for shared librarys"
            }
        }
    }
}
