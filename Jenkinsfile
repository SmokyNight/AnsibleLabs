pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                git branch: 'main', url: 'https://github.com/SmokyNight/AnsibleLabs.git'
                sh 'echo 123'
            }
        }
    }
}
