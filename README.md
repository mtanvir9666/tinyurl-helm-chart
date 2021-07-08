# Getting Started

## How to publish helm chart to github pages
- tinyurl-helm-chart> Copy individual helm chart under allcharts directory (Example: chart for urladmin, urlfinder etc.)
- tinyurl-helm-chart> helm package allcharts/*   [ This will create tarballs corresponding to the individual charts ]
- tinyurl-helm-chart> helm repo index --url https://mtanvir9666.github.io/tinyurl-helm-chart/ . [ This will create the index.yaml file]

## Reference
https://medium.com/@mattiaperi/create-a-public-helm-chart-repository-with-github-pages-49b180dbb417