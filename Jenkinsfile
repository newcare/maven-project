pipeline {
    agent any
    stages{
        stage ('Build Package'){
            steps {
                build job: 'package'
            }
        }
            stage ('first jenkins job'){
                steps {
                build job: 'deploy-to-staging'
                }
     
            post {
                success {
                    echo 'Pipeline is ok'
                }
            }
            }
            
                }
        }
