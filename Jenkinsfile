pipeline {
    agent any

    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation deploy --template-file https://github.com/eerm1234/JenkinsPipelineDemo/blob/master/JenkinsEC2.yaml --stack-name myteststack --region 'eu-central-1'"
            }
        }
    }
}
