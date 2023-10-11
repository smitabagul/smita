pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo "Hello Worl"
            }
        }
    }
    post { 
        always { 
            echo "I will always say Hello again!"
        }
    }
}
