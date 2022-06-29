## Pipeline Process

## DEV

- First Dev creates RDS manually to be able to connect to EB when active

## REPO

- Dev creates a new repo on github for example then push the data from local pc to to github using Git Commands

## CircleCi (CI)

- checks if the repo changed then it start processing the build-test-deploy steps to be able to push the data to AWS
- building an app just creates its final build that work on browsers
- testing an app to check if there is any errors inside the app because if there is any error in mirge it will not proceed 
- CI push backend data to Elastic beanstalk
- CI push frontend data to S3 Storage
- CI saves secret env data
