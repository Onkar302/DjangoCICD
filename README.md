# DjangoCICD
 This project is for CI/CD pipeline.
 Flow is:
 1. Webhook trigger Jenkins CICD Job
 2. jenkins controller passes job to be built to agent where:
    i) Code is pulled.
    ii) Docker image is built (If tests run it).
    iii) Deploy (currently on local agent which executes the job.
