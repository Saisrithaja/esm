pipeline {
    agent any

    stages {
        stage(("Checkout")) {
            steps {
                git brach: "main",url:"https://github.com/Saisrithaja/esm.git"
            }
        }
        stage(("Compile")) {
            steps {
                sh "javac sample.java"
            }
        }
        stage(("Run")) {
            steps {
                sh "java sample"
            }
        }
    }
}