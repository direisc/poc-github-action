# Hello world JavaScript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

Use a release tag (`@v1` or `@vX.Y.Z`). `@main` is not supported — the runnable `dist/` bundle exists only on release tags.

```yaml
uses: direisc/poc-github-action@v1
with:
  who-to-greet: Mona the Octocat
```
