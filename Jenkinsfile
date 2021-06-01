pipeline {
    agent {
        node { label "maven" }
    }
    stages {

        stage("Test") {
            steps {
                h "./mvnw verify"
            }
        }

    }
}