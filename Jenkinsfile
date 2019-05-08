pipeline {
    agent { label 'master' }
    stages {
        stage('git_clone_demo') {
            steps {
                echo 'Hello world!' 
                git credentialsId: '8354138e-1feb-4472-b9d8-dafd0a5f3c95', url: 'https://github.com/rachamaduguudaykumar/uday.git'
            }
        }
    stage('Build') {
        steps {
            echo 'helloword'
            sh '''
            mvn clean
            mvn compile
            mvn test
            mvn package
            '''
        }
    }
    stage('Unittests') {
        steps {
            echo 'helloword'
        }
    }
    stage('sonar') {
        steps {
            echo 'helloword'
        }
    }
    stage('artifactory') {
        steps {
            echo 'helloword'
        }
    }
    stage('deploy') {
        steps {
            echo 'helloword'
        }
    }
    }
}
