# agreed-typed

- agreed api type definitions (types.ts)
- agreed.ts to swagger generator

## generate swagger
```shell
$ yarn gen-swagger [...agreed (ts) file paths]
```

### example
```shell
$ yarn gen-swagger __tests__/data/agrees-get.ts __tests__/data/agrees-post.ts
```

```$xslt
$ agreed-server --path ./agreed.ts --port 3010
```

```
$ curl http://localhost:3010/user/yosuke?q=foo
```
