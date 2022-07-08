pipeline {
    agent any

    stages {
        stage('Onboard') {
            steps {
                echo 'Hello World'
                testBase useConfigurationFile: true, configurationFilePath: 'TestBase.json'
            }
        }
    }
}