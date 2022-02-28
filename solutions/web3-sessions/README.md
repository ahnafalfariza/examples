# web3-sessions

This example shows how create sessions in Next.js with [Metamask](https://metamask.io/) and [NextAuth.js](https://next-auth.js.org/).

## Demo

to do update

https://web3-sessions.vercel.app

This Demo will show how to configure NextAuth.js and create a custom hook to protect routes.

## How to Use

You will need to add the proper variables in a `.env` file like show in the `.env.example` file.

```
// generate random secrets on https://passwordsgenerator.net/ or anywhere else similar
NEXT_AUTH_SECRET=:2f6U'GW\"kc5v-r
JWT_SECRET=7KY(6sMwVXmkqG@Q
```

You can choose from one of the following two methods to use this repository:

### One-Click Deploy

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=next-example):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/vercel/examples/tree/main/solutions/web3-sessions&project-name=web3-sessions&repository-name=web3-sessions)

### Clone and Deploy

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```bash
npx create-next-app --example https://github.com/vercel/examples/tree/main/solutions/web3-sessions
# or
yarn create next-app --example https://github.com/vercel/examples/tree/main/solutions/web3-sessions
```

Next, run Next.js in development mode:

```bash
npm install
npm run dev

# or

yarn
yarn dev
```

Deploy it to the cloud with [Vercel](https://vercel.com/new?utm_source=github&utm_medium=readme&utm_campaign=edge-middleware-eap) ([Documentation](https://nextjs.org/docs/deployment)).