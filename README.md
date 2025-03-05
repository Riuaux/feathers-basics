Trying FeathersJS v5

> https://feathersjs.com/guides/basics/starting.html

Commands history:

```bash
mkdir feathers-basics
cd feathers-basics
pnpm init
git init # and .gitignore
pnpm add typescript ts-node @types/node --save-dev
npx tsc --init --target es2020

pnpm add @feathersjs/feathers --save
# Setup app.ts file, then
npx ts-node app.ts

pnpm add @feathersjs/socketio @feathersjs/koa --save
# Update app.ts file, then
npx ts-node app.ts
# Visit http://localhost:3030/messages to check
# Setup index.html file then http://localhost:3030 to check
```
