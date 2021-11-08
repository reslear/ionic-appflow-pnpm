# ionic-appflow-pnpm
how to use pnpm in ionic appflow

# in you `appflow.config.json`

```json
{
  "apps": [
    {
      "appId": "id",
      "root": "frontend",
      "dependencyInstallCommand": "npm i -g pnpm && pnpm i --filter=frontend",
      "webBuildCommand": "pnpm build --filter=frontend"
    }
  ]
}
```
