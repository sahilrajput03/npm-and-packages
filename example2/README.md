# Readme

I manually added below text to `package.json`:

```json
 "workspaces": [
    "packages/*"
  ]
```

and run `npm i` to create a `package-lock.json` and `node_modules` with appropriate symlinks.
