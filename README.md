# technodot

who am i?<br>
good question! let's find out together.

## Hosting

The static SvelteKit site is hosted on Cloudflare Pages. Pushes to `main` and
manual runs of the `deploy` workflow on `main` install dependencies with
`bun install --frozen-lockfile`, build with `bun run build`, and upload the
`build` directory with Wrangler. The workflow pins Bun and Wrangler versions.

The Pages project, custom domain, and DNS are managed by Terraform in
[TechDudie/iac](https://github.com/TechDudie/iac). GitHub Actions uses the
`CLOUDFLARE_PAGES_API_TOKEN` secret and the `CLOUDFLARE_ACCOUNT_ID` and
`CLOUDFLARE_PAGES_URL` variables. The token needs account-scoped Cloudflare Pages
edit permission. Keep it in sync with the **production** environment secret
of the same name in the infrastructure repo when rotating it.
