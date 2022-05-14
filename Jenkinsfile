pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh '''
                    dir
                    python3 hi.py
                   ''' 
            }
        }
    }
}
