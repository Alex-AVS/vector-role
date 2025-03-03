pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Get code from a GitHub repository
                git branch: 'main', url: 'https://github.com/Alex-AVS/vector-role.git'

                // Run molecule.
                sh "molecule test"

            }
        }
    }
}
