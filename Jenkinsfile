pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                testBase configurationFilePath: 'TestBase.json', useJenkinsOptions: true
            }
        }
    }
}