pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                sh "/opt/apache-maven-3.8.6/bin/mvn package"
            }
        }
        stage('Deploy') {
            steps {
                sh "/opt/apache-maven-3.8.6/bin/mvn test"
            }
        }
    }
}
