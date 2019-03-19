# custom-prisma-generate

```bash
npm i --save-dev custom-prisma-generate
```

add this to file 'prisma.yml'

```yaml
hooks:
  post-deploy:
    - npx custom-prisma-generate --input ./prisma/datamodel.prisma --output ./src/generated/prisma-type.ts
```
