pipeline {
    agent any
    
    stages {
        stage("compilar") {
            steps {
                dir("vaquesrest") {
                    
                        sh 'mvn compile'
                    
                }
            }
        }
        stage("tests") {
            steps {
                dir("vaquesrest") {
                    sh "mvn test"
                }
            }
        }
        stage("Mes coses") {
            steps {
                echo "Més coses"
            }
        }
    }
}