pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Hello DevOps') {
            steps {
                echo 'Jenkins has successfully loaded our pipeline!'
                echo 'Next: Maven build, tests and SonarQube.'
            }
        }
    }
}
