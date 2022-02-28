pipeline {
    agent any

    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation deploy --template-file /home/eero/Documents/JenkinsEC2.yaml | describe-stack-events --stack-name myteststack --region 'eu-central-1'"
            }
        }
    }
}
