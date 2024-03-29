# bookish-robot

**Frontend**

- VueJS - For client facing and internal apps.
- NuxtJS - for Some Services that require to be server side rendered

**Backend**

- PHP - Most of the Backend Infrastructure
- Node JS - Some services including PDF-generating services
- AWS Lambda - for PDF-generating services

**Cloud**

- AWS
    - AWS EC2 - This houses our main server(s).
    - AWS S3 - For storage
    - AWS RDS - Oracle Database
    - AWS Cloudfront - Distribution network for many of the assests on the app.
    - AWS Lambda - Serverless functions for some services.
    - API Gateway - A proxy to other AWS Services, also rate limits requests.

**Version Cotrol**

- Github

**CI**

- Github CI
- AWS CodePipeline

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```
