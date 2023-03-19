pipeline {
    agent any{
    }
    stages {
        stage("build") {
            steps {
                echo("hello is build")
            }
        }
         stage("test") {
            steps {
                echo("hello is test")
            }
        }
         stage("ddeploy") {
            steps {
                echo("hello is deploy")
            }
        }
    }
    post {
        always {
            echo "don't worry is started"
        }
         success {
            echo "congratulations"
        }
         failure {
            echo "please try again and check the error"
        }
         cleanup {
            echo "don't worry is check to clean"
        }
    }
}