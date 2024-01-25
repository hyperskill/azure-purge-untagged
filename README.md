# azure purge untagged
Hyperskill GitHub Action | Logins to Azure Container Registry and purges untagged manifests

```yaml
- uses: hyperskill/azure-purge-untagged@v2.0.0
  with:
    client_id: ${{ secrets.CLIENT_ID }}
    client_secret: ${{ secrets.CLIENT_SECRET }}
    subscription_id: ${{ secrets.SUBSCRIPTION_ID }}
    tenant_id: ${{ secrets.TENANT_ID }}
    repository_filter: my_repo
    registry: myazureregistry
```
