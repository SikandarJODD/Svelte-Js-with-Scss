<style>
  .co{
  transition:all 0.3s ease;
  color:royalblue;
  }
  .co:hover{
  transition:all 0.3s ease;
    color:#025de7;
  }
  h1{
  color:#1f1f1f;
  border:1px solid black;
  border-radius:4px;
  padding:10px;
  text-align:center;
  box-shadow:4px 4px black;
  }
</style>
<img src="svsass.jpg" alt="Svelte Js with Scss" style="width:700px;"/>

<h1> Svelte-Js with <span class="co">Scss</span></h1>

Adding Scss to Svelte Js

## Installation

Install Svelte with vite

```bash
  npm create vite@latest
```

```bash
  Project name : project
  Framework : SvelteJs
  Language : JavaScript

```

```bash
  cd project
  npm i
```

```bash
  npm i svelte-preprocess node-sass --save--dev
  npm i sass --save--dev
```

## Edti vite.config.js

```bash
    import { defineConfig } from 'vite'
    import { svelte } from '@sveltejs/vite-plugin-svelte'
    import { sveltePreprocess } from 'svelte-preprocess/dist/autoProcess'

    // https://vitejs.dev/config/
    export default defineConfig({
    plugins: [svelte({
        preprocess: sveltePreprocess()
    })],
    })

```

Restart the <a>VS-Code</a> and Run the Command

```bash
  npm run dev
```

Project : [Localhost:5173](http://localhost:5173)

## package.json Code :

![Screenshot](PackageImg.PNG)

## Running on port : 5173

![Screenshot](output.png)

## Scss Code in App.svelte

![Screenshot](Code.PNG)
