pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh (""" 
                python test.py 
                """)
            }
        }
    }
}
