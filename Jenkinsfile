pipeline {
    agent any

<<<<<<< HEAD
    tools {
        jdk 'JDK8'
    }

    stages {

        stage('Compile') {
            steps {
                echo 'Compiling Java program'
                bat 'javac src\\com\\tyit\\HelloJenkins.java'
            }
        }

        stage('Run') {
            steps {
                echo 'Running Java program'
                bat 'java -cp src com.tyit.HelloJenkins'
            }
        }
    }

    post {
        success {
            echo 'Java build executed successfully in Jenkins'
        }
        failure {
            echo 'Java build failed'
=======
    stages {
        stage('Checkout') {
            steps {
                echo 'Cloning repository'
                git 'https://github.com/sweta-suman1/MSC-IT-P1.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application'
            }
>>>>>>> b3a61215b1be639df9cb0efb1c2616df44c1649e
        }
    }
}
