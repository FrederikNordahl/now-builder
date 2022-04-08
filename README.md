# Frontity - Now builder FORKED from [Frontity now-builder](https://github.com/frontity/now-builder)

This builder attempts to stay updated with vercel, so it will work with SWR and caching.

## Before deploying

1. Create this `vercel.json` file in your project and change the site url:

```json
{
  "builds": [
    {
      "src": "package.json",
      "use": "@frederiknordahl/now"
    }
  ]
}
```

2. Follow the rest of the guide on [Deploy Frontity using Vercel](https://gitbook-docs.frontity.org/deployment/deploy-using-vercel)
