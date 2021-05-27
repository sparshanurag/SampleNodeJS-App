@Library("shared-library") _
pipeline {
    agent any

    stages {
        stage('Git') {
            steps {
                git branch: 'dev', url: 'https://github.com/sparshanurag/SampleNodeJS-App'
            }
        }
         stage('deploy') {
            steps {
                deploy()
            }
        }
    }
}
