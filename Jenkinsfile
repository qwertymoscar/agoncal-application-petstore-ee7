pipeline {
    agent any
    tools {
        maven 'maven363'
    }
    stages {
        stage('Print Message') {
            steps {
                echo "First test [print message]"
                sh 'mvn --version'
            }
        }
    }
}
