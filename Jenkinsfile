pipeline {
    agent any
    environment { 
        CC = 'gcc'
    }
    stages {
        stage('Example') {
            environment { 
                AN_ACCESS_KEY = credentials('311f6fcb-6920-467c-837e-ba07e19afd43') 
            }
            steps {
                sh 'printenv'
                sh 'echo ${AN_ACCESS_KEY}'
            }
        }
    }
}
