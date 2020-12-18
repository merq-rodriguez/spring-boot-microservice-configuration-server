# SPRING BOOT CONFIG SERVICE

# GET CONFIGURATION

Get configuration of items service:

```
  http://localhost:8888/items-service/default
```

Get configuration of products service:

```
  http://localhost:8888/products-service/default
```

### Responses

```json
{
  "name": "product-items-service",
  "profiles": [
    "default"
  ],
  "label": null,
  "version": "2ebeb32fa60c59be15fbc3f9b481fad17da17f85",
  "state": null,
  "propertySources": [
    {
      "name": "file:/path.../Config/product-items-service.properties",
      "source": {
        "server.port": "6000",
        "configuration.label": "Quantum"
      }
    }
  ]
}
```
