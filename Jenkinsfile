pipeline {
    agent any
    stages {
        stage('git clone') {
            steps {
              git branch: '${Branch}', credentialsId: 'git', url: 'https://github.com/dsilvarodney1/python-for-devops'
            }
        }
        stage('build'){
            setps{
                sh 'printenv'
            }
        }
    }
}
