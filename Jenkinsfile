pipeline {
    agent any
    stages {
        stage('Upload to AWS') {
            withAWS(region: 'us-east-2', credentials:'aws-static')  {
                s3Upload(file:'index.html', bucket: 'udacity.nanodegree.cloud-devops-engineer.jenkins', path:'index.html')

            }
        }
    }
}