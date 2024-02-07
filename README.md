# commitlint-config

:point_right: https://cbea.ms/git-commit/

## Usage

```
npm i -g @well-crafted/commitlint-config
npx --yes --package="@commitlint/cli" --package="@well-crafted/commitlint-config" \
  commitlint --extends "@well-crafted/commitlint-config" --edit
```

Installing `@well-crafted/commitlint-config` globally is required as a workaround for as long as
https://github.com/conventional-changelog/commitlint/issues/613 isn't fixed.
