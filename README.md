# alanbates.tech

This repo holds a personal portfolio web site.

It is hosted on GCP.

It features CI/CD integration with GCP.  Any time code is pushed from local to origin, the data is pulled into the GCS bucket automatically using a Google Cloud Build trigger and the cloudbuild.yaml file.

![Image of Architecture](https://raw.githubusercontent.com/alanjbates/PySpark_Classification_Using_LogisticRegression/master/gcp_hosted_static_website_cicd.png)
