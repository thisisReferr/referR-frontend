### Contribution Guideline

1. Create a new branch from `dev` and push you changes there
2. Create a PR and target the `dev` branch instead of `main`
3. PRs from `feature-branch` to `dev` will be squash merged
4. PRs from `dev` to `main` will be merged as default
5. Always run prettier before pushing your code

```bash
npm run format:fix
```

### Setting up your Local Codebase

1. Installs dependencies

```bash
npm i --save
```

2. Create a new `.env` file by copying the `.env.example` file

3. Run the app

```bash
npm run dev
```

4. Format Code

```bash
npm run format:fix
```

5. Check Formatting

```bash
npm run format:check
```

6. Check Linting

```bash
npm run lint
```
