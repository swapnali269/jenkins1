pipeline {
    agent any
        environment {
            PATH = "/etc/maven/bin:$PATH"
        }

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
         
    
