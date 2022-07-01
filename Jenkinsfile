pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                greet configurationFilePath: 'TestBase.json', name: 'bingoz', useJenkinsOptions: true
            }
        }
    }
}
