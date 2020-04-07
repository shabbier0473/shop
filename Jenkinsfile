pipeline{
    agent any
    tools { maven "MAVEN_HOME" }
    stages{
        stage ('build'){
            steps{
                 sh 'mvn --version'
                 sh 'mvn clean install' 
            }
        }
    }
}
