pipeline {
    agent any

    stages {
        stage("git checkout ") {
            steps {
                git branch: 'main', url: 'https://github.com/syedsarmas/pest1.git'   
            }
        }
        stage("hello world") {
            steps {
                sh 'echo "hello world"'
            }
        }
    }
}






