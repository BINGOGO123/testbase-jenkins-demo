pipeline {
    agent any

    stages {
        stage('onboard') {
            steps {
                testBase useConfigurationFile: true, configurationFilePath: 'TestBase.json', credentialsId: 'clientsecret'
            }
        }
    }
}