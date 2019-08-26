*Psst — looking for a shareable component template? Go here --> [sveltejs/component-template](https://github.com/sveltejs/component-template)*

---

# svelte app

A project template for [Svelte](https://svelte.dev) apps based on https://github.com/sveltejs/template with
* [Bulma](https://bulma.io/)
* [svelte-preprocess](https://github.com/kaisermann/svelte-preprocess)
* [postcss](https://github.com/postcss/postcss)
  * [autoprefixer](https://github.com/postcss/autoprefixer)
* [sass](https://github.com/sass/node-sass)

To create a new project based on this template using [degit](https://github.com/Rich-Harris/degit):

```bash
npx degit RudySchockaert-EngieIT/svelte-bulma-template svelte-app
cd svelte-app
```

*Note that you will need to have [Node.js](https://nodejs.org) installed.*


## Get started

Install the dependencies...

```bash
cd svelte-app
npm install
```

...then start [Rollup](https://rollupjs.org):

```bash
npm run dev
```

Navigate to [localhost:5000](http://localhost:5000). You should see your app running. Edit a component file in `src`, save it, and reload the page to see your changes.


## Deploying to the web

### With [now](https://zeit.co/now)

Install `now` if you haven't already:

```bash
npm install -g now
```

Then, from within your project folder:

```bash
cd public
now
```

As an alternative, use the [Now desktop client](https://zeit.co/download) and simply drag the unzipped project folder to the taskbar icon.

### With [surge](https://surge.sh/)

Install `surge` if you haven't already:

```bash
npm install -g surge
```

Then, from within your project folder:

```bash
npm run build
surge public
```
