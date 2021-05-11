## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/floriapp/floriapp-helm/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

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
