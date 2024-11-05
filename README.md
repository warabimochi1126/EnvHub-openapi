# インストール

```
npm i -g @redocly/cli@latest
```

# redoc ローカル起動

```
redocly preview-docs .\openapi.yaml
```

# TypeScript 型生成

```
npx @hey-api/openapi-ts -i .\openapi\openapi.yaml -o src/client -c @hey-api/client-fetch
```

# actions 発火手順

- `openapi.yaml` を書きかえる
- `package.json` の `version` を上げる
- `main` に `push` する
