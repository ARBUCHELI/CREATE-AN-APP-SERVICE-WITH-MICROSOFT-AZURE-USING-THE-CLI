# CREATE-AN-APP-SERVICE-WITH-MICROSOFT-AZURE

* Creating app service
```
az login
```

```
az webapp up \
 --resource-group resource-group-west \
 --name hello-world1234 \
 --sku F1 \
 --verbose
```

* If the app is updated
```
az webapp up \
 --name hello-world1234 \
 --verbose
```

* Delete an app service
```
az webapp delete \
    --name hello-world1234 \
    --resource-group resource-group-west
```

* Delete an app service plan
```
az appservice plan delete \
    --name [App Service Plan Name] \
    --resource-group resource-group-west
```
