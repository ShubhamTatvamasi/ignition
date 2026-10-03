# ignition

Get the `admin` password:
```bash
kubectl -n ignition get secret ignition-gateway-admin-password \
  -o jsonpath='{.data.gateway-admin-password}' | base64 -d; echo
```

