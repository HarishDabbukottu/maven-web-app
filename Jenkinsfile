pipeline {
    agent any
    
    tools{
        maven 'Maven-3.9.11'
    }
    stages {
        stage('clone') {
            steps {
              git 'https://github.com/ashokitschool/maven-web-app.git'
            }
        }
        stage('build'){
            steps{
                 sh 'mvn clean package'
            }
        }
       
    }
}
