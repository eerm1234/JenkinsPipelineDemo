pipeline {
    agent any

    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --template-body file://JenkinsEC2.yaml --stack-name myteststack --region 'eu-central-1'"
            }
        }
    }
}
