pipeline {
    agent any
    stages {
        stage('Build'){
            steps {
                echo 'running build automaton'
                sh './gradle build'
                archiveArtifacts artifacts: 'dist/trainschedule.zip'
            }
        }
    }
}
