pipeline {
    agent any
    stages {
        withAWS(region: 'us-east-2', credentials:'aws-static')  {
            s3Upload(file:’index.html', bucket: 'arn:aws:s3:::udacity.nanodegree.cloud-devops-engineer.jenkins', path:'index.html')

        }
    }
}