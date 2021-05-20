pipeline {
    agent any

    stages {
        stage('Git') {
            steps {
                git branch: 'test', url: 'https://github.com/sparshanurag/SampleNodeJS-App'            }
        }
         stage('deploy') {
            steps {
                sh "node main.js "
            }
        }
    }
}
