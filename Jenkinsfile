pipeline {
    agent any
    stages {
        stage('Build'){
            steps {
                echo 'running build automaton'
                sh './gradlew build'
                archiveArtifacts artifacts: 'dist/trainschedule.zip'
            }
        }
    }
}
