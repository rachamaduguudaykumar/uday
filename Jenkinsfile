pipeline {
    agent { label 'master' }
    stages {
        stage('git_clone_https://github.com/rachamaduguudaykumar/uday.git') {
            steps {
                echo 'Hello world!' 
             
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
