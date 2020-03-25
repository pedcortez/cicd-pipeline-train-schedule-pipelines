pipeline {
    agent any
    stages {
        stage('Build'){
            steps {
                echo 'running build automaton'
                sh './gradlew npm_start'
                archiveArtifacts artifacts: 'dist/trainschedule.zip'
            }
        }
    }
}
