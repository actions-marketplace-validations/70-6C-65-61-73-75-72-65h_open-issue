# GH Issue Action

This action opens a new gh issue

## Inputs

### `token`

**Required** GH token

### `title`

**Required** GH title

### `body`

### `assignees`

## Example usage

```yaml
uses: 70-6C-65-61-73-75-72-65h/issue-action@v1
with:
  token: ${{ secrets.GITHUB_TOKEN }}
  title: Title
  body: Body
  assignees: |
    ${{ github.event.pull_request.user.login }}
    Maksym-Ulshyn
```
