# 👷 `noebs wasm interface for encryption


A ready rsa encrypt for your next frontend project. It can be integrated to your angular, react, or any js project. Or you can host it on a cloud provider as a serverless app.

#### Wrangler

To generate using [wrangler](https://github.com/cloudflare/wrangler)

```
wrangler generate projectname https://github.com/cloudflare/worker-template
```

#### Serverless

To deploy using serverless add a [`serverless.yml`](https://serverless.com/framework/docs/providers/cloudflare/) file.


##### Building go app

```shell
# go to wasm dir
$ cd wasm
$ GOOS=js GOARCH=wasm go build -o main.wasm
```

