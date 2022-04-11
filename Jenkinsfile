pipeline {
    agent any

    stages {
        stage('Init') {
            steps {
                //gh repo clone VishnukumarDhanarajan/JavaHelloWorld
                //git 'https://github.com/VishnukumarDhanarajan/JavaHelloWorld.git'
                 bat "java Helloworld.java"
            }

            post {
                success {
                    echo 'Success'
                }
            }
        }
    }
}
