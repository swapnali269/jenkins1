pipeline {
    agent any

    stages {
        stage ('git') {
            steps {
                git 'https://github.com/swapnali269/jenkins1.git'
            }
        }
        stage ('build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
         
    
