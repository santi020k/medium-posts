# medium-posts

Companion **Next.js** examples and scaffolding referenced from articles on [**Medium @santi020k**](https://medium.com/@santi020k). Branches and paths here map to posts about tooling, ESLint, testing, and app structure.

> [!IMPORTANT]
> This is educational snapshot code, not a production application or a starter
> recommended for new projects. The examples intentionally remain on the Next 14
> and Storybook 8 generation used by the accompanying articles.

- **Site & blog:** [santi020k.com](https://santi020k.com) · [Blog](https://santi020k.com/blog)
- **Primary ESLint package:** [@santi020k/eslint-config-basic](https://github.com/santi020k/eslint-config-basic)

---

## Getting started

This is a [Next.js](https://nextjs.org/) app. Use the scripts in `package.json`:

```sh
npm ci
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to explore the project.

## Validate the examples

```sh
npm run verify
```

This runs linting, 18 component tests, the Next.js production build, and the
Storybook static build. GitHub Actions is intentionally disabled so this
reference repository does not consume runner minutes.

## Security

Do not deploy this educational snapshot as a public service. Report sensitive
issues through the repository's Security tab; see [SECURITY.md](SECURITY.md).

## Learn more

- [Next.js documentation](https://nextjs.org/docs)
- [Next.js learn](https://nextjs.org/learn)
