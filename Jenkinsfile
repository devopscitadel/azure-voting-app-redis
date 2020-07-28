Pipeline {
    agent any

    stages {
        stage('Verify branch') {
            steps {
                echo "$GIT_BRANCH"
            }
        }
        stage('Goodbye Hello') {
            steps {
                echo 'Goodbye World'
            }
        }
        stage('Print env variabled') {
            steps {
                sh label: '', script: 'printenv'
            }
        }
    }
}
