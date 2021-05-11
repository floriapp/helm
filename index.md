## Flori.App Helm Charts repository
Adding the chart repository:

helm repo add floriapp https://floriapp.github.io/helm/
Adding Flori.App chart repository to Rancher 2.5+:

Go to Cluster Explorer > Apps & Marketplace > Chart Repositories
Click Create
Fill in the fields
  Name: floriapp
  Target: Https url to helm index
  Index URL: https://floriapp.github.io/helm/
