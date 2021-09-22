pipeline{
    agent any

    stages {
        // week1-day2-abhishek-jenkins-pipeline-assignment
        stage('compile'){
            steps {
                bat 'mvn clean compile'
            }
        }
        
        stage('unit test'){
            steps {
                bat 'mvn test'
            }
        }
        
        stage('build'){
            steps {
                bat 'mvn -DskipTests package'
            }
        }
        
        stage('image'){
            steps {
                echo 'creating docker image...'
            }
        }

    }

}
