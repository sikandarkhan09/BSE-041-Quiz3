pipeline {
    agent any
    stages {
        stage('Compile and Run Java') {
            steps {
                sh 'javac HelloWorld.java'
                sh 'java HelloWorld'
            }
        }
    }
}
