# Svelte-D3-app template

> Template based on the official [Svelte app template](https://github.com/sveltejs/template)


## Get it
```bash
npx degit higsch/svelte-d3-template app
cd svelte-app
```


## Start it

```bash
cd app
npm install
npm run dev
```

Navigate to [localhost:5000](http://localhost:5000). You should see your app running.


## Build it

```bash
npm run build
```


## Deploying it

### With [Vercel](https://vercel.com)

Install `vercel` if you haven't already:

```bash
npm install -g vercel
```

Then, from within your project folder:

```bash
cd public
vercel deploy --name my-project
```

### With [surge](https://surge.sh/)

Install `surge` if you haven't already:

```bash
npm install -g surge
```

Then, from within your project folder:

```bash
npm run build
surge public my-project.surge.sh
```
