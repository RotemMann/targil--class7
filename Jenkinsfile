pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bash '''
                     dir
                     python hi.py
                    ''' 
            }
        }
    }
}
