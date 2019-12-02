# Reproduction

The packages must be installed with `pnpm@3.8.1`:

```sh
npm install -g pnpm@3.8.1
```

Install packages with pnpm

```sh
pnpm install --force
```

Build the project

```sh
npm run build
```

You should then get the following error:

```sh
> tsc --project ./server/tsconfig.json --outDir .server

../../common/temp/node_modules/.registry.npmjs.org/apollo-engine-reporting-protobuf/0.4.4/node_modules/apollo-engine-reporting-protobuf/dist/protobuf.d.ts:1:23 - error TS2307: Cannot find module 'long'.

1 import * as Long from "long";
                        ~~~~~~
```
