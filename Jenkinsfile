pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat '''
                     dir
                     python hi.py
                    ''' 
            }
        }
    }
}
