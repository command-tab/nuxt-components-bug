# nuxt-components-bug

To repro:

```bash
$ yarn install
$ yarn run dev
# observe that both components load images in dev

$ yarn run build
$ yarn run start
# observe that @command-tab/place-kitten does not load in this production build
```
