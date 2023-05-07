pipeline {
    agent any
    stages {
    stage('git clone') {
            steps {
               git branch: 'main', url: 'https://github.com/aayushknoldus03/PRfinalcapestone '
            }
        }
          stage('Testing result') {
            steps {
                sh 'echo Test successfull'
            }
        }
     }
 }
