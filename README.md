# commitlint-config

:point_right: https://cbea.ms/git-commit/

## Usage

```
npm i -g @carhartl/commitlint-config
npx --yes --package="@commitlint/cli" --package="@carhartl/commitlint-config" \
  commitlint --extends "@carhartl/commitlint-config" --edit
```

Installing `@carhartl/commitlint-config` globally is required as a workaround for as long as
https://github.com/conventional-changelog/commitlint/issues/613 isn't fixed.
