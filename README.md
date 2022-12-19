# choreo-container-registry-login

This action configs the login to contianer regisrty based on the tye. Defualt one is ACR

## Inputs

### `type`

**Required** 'Container Registry Type. Default `"ACR"`.

## Example usage

```yaml
uses: choreo-templates/choreo-container-registry-login@v1.0
with:
  type: 'ACR'
```