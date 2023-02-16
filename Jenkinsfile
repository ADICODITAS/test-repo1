pipeline {
    agent any
    stages {
        stage('Clone Git Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/ADICODITAS/test-repo1.git'
            }
        }
        stage('Run Shell Script') {
            steps {
                sh ./hii.sh
            }
        }
    }
}
