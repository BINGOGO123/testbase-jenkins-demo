pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                greet configurationFilePath: 'TestBase.json', useJenkinsOptions: true
            }
        }
    }
}
