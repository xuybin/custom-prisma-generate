# custom-prisma-generate

```bash
npm i --save-dev custom-prisma-generate
```

add this to file 'prisma.yml'

```yaml
hooks:
  post-deploy:
    - npx custom-prisma-generate --output ./src/generated/custom-prisma
```
