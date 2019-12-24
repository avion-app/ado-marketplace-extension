# ado-marketplace-extension

First, install the TFS CLI:

```
npm i -g tfx-cli
```

Then, make changes and package up into marketplace VSIX file:

```
tfx extension create --manifest-globs vss-integration.json
```
