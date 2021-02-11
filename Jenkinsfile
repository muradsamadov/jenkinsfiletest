pipeline {
    agent any

    stages {
        stage ('Compile Stage') {
            
            steps {
                withMaven(maven: 'jenkins_maven') {
                    sh 'mvn package'
                }



            }

        }






    }



}