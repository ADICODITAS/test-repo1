pipeline {
    agent any
    stages {
        stage('Clone Git Repository') {
            steps {
                git 'https://github.com/ADICODITAS/test-repo1.git'
            }
        }
        stage('Run Shell Script') {
            steps {
                sh './hii.sh'
            }
        }
    }
}
