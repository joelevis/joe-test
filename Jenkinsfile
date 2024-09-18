pipeline {
    agent { label 'docker24' }
    
    parameters {
        string defaultValue: 'FizzBuzz', name: 'PARAM1', trim: true
    }

    stages {
        stage('Build') {
            steps {
                sh '''
                    pwd
                    echo "This is a test"
                    echo "This is a parameter: $PARAM1"
                    
                '''
            }
        }
    }
}
