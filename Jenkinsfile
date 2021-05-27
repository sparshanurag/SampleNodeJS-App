@Library("shared-library") _
pipeline {
    agent any

    stages {
        stage('Git') {
            steps {
                git branch: 'test', url: 'https://github.com/sparshanurag/SampleNodeJS-App'            }
        }
         stage('deploy') {
            steps {
                deploy()
            }
        }
    }
}
