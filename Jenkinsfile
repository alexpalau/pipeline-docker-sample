pipeline {
    agent {
        dockerfile true
    }
    stages{
        stage('Example'){
            steps{
                echo 'Hello World from Develop Again!!'
                sh 'echo myCustomVar = $myCustomVar'
            }
        }
    }
}