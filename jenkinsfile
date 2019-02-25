pipeline {
    agent any 
    stages {
        stage('continuousdownload') { 
            steps {
                git 'http://github.com/selenium-saikrishna/maven.git'
                 
            }
        }  
    stage('continuousbuild') 
    {
        steps  { 
            sh label: '', script: 'mvn package'
            }
    }
}