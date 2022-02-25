pipeline {
    agent any

    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation deploy --template-file /home/eero/Documents/JenkinsEC2.yaml --stack-name my-new-stack --region 'eu-central-1a'"
            }
        }
    }
}
