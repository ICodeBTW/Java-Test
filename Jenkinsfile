 pipeline {
    agent any  

    stages {
        stage("hello") {
            steps {
                script{
                    sh "docker run --rm -v `pwd`:/home/build java-build sh builder.sh"
                }
            }
        }
    }
 }
