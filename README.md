# Issue repro Prisma

How to run

```bash
npm install
npx ts-node src/index.ts
```

Expected output

```json
["\"\"", 0]
```

Actual output

```json
["""",0]
```
