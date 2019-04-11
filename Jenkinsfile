pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'CocosCreator/CocosCreator.exe --path ./ --build'
            }
        }
    }
}
