# Conventional Commits workflow

A zero-dependency GitHub Actions workflow that checks pull request titles and
commit subjects against the [Conventional Commits](https://www.conventionalcommits.org/)
format.

It accepts these commit types:

`build`, `chore`, `ci`, `docs`, `feat`, `fix`, `perf`, `refactor`, `revert`,
`style`, and `test`.

Subjects must be shorter than 72 characters. Scopes and breaking-change `!`
markers are supported.

## Install

Copy [`.github/workflows/conventional-commits.yml`](.github/workflows/conventional-commits.yml)
into the same path in your repository.

```sh
mkdir -p .github/workflows
curl -o .github/workflows/conventional-commits.yml \
  https://raw.githubusercontent.com/skyth3r/conventional-commits-workflow/main/.github/workflows/conventional-commits.yml
```

## License

[MIT](LICENSE)
