# CV Benjamin Bordes

My CV developed in pug and stylus (HTML and CSS preprocessors).

- [bbordes.fr](https://bbordes.fr)
- [bbordes.fr/en](https://bbordes.fr/en)
- [PDF - FR](https://bbordes.fr/CV%20Benjamin%20Bordes%202024.pdf)
- [PDF - EN](https://bbordes.fr/en/CV%20Benjamin%20Bordes%202024.en.pdf)

A GitHub action updates my AWS S3 bucket and invalidates CloudFront's cache.
I use OVH as my registrar, Cloudflare as my DNS provider and CloudFront for fast content delivery.

This online CV project has been incredibly rewarding, allowing me to learn extensively from the diverse technologies used in its development and deployment.

## Development

Using the package manager of your choice: npm, yarn, pnpm, bun, dino, etc.

Install browser-sync

```shell
pnpm i -g browser-sync
```

Start the development server which reloads the browser when files change:

```shell
pnpm start
```
