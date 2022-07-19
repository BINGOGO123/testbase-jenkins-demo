pipeline {
    agent any

    stages {
        stage('onboard') {
            steps {
                testBase useConfigurationFile: true, configurationFilePath: 'TestBase-df.json', credentialsId: 'dfclientsecret'
            }
        }
    }
}