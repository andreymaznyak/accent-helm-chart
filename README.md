Helm chart for [accent project](https://github.com/mirego/accent)

How to install:
1. Create prod-values.yml file with your credentials - [example file](https://github.com/andreymaznyak/accent-helm-chart/blob/master/accent-chart/values.yaml)
1. Setup helm chart
```
helm install --name prod-translate accent-chart -f prod-values.yml
```
