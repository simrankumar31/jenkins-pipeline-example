pipeline{
    agent any

    stages {
        // week1-day2-abhishek-jenkins-pipeline-assignment
        stage('compile'){
            steps {
                sh 'mvn clean compile'
            }
        }
        
        stage('unit test'){
            steps {
                sh 'mvn test'
            }
        }
        
        stage('build'){
            steps {
                sh 'mvn -DskipTests package'
            }
        }
        
        stage('image'){
            steps {
                echo 'creating docker image...'
            }
        }

    }

}