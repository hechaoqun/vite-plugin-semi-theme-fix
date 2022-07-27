# vite-plugin-semi-theme-fix
基于【vite-plugin-semi-theme】修复版本


- [theme options docs](https://github.com/DouyinFE/semi-design/tree/main/packages/semi-webpack#api)

```js
// vite.config.js
import { defineConfig } from "vite";
import semi from "vite-plugin-semi-theme-fix";

export default defineConfig({
  plugins: [
    semi({
      theme: "@semi-bot/semi-theme-yours",
      // options: {
      // ... 👆
      //},
    }),
  ],
});
```
