> [!NOTE]
> Use [gh-artifact-purge](https://github.com/andyfeller/gh-artifact-purge) instead.

# gh-delete-artifacts

Delete all GitHub Actions artifacts for a repository or an entire organization.

> [!WARNING]
> This is a destructive action. Once artifacts are deleted, they cannot be recovered.

## 📦 Install
```bash
gh extension install austenstone/gh-delete-artifacts
```

## ⚡️ Usage
Run
```bash
➜ gh delete-artifacts --help

  Usage: delete-artifacts [options]

  Options:
    -o, --org <org>               The organization to query for deleting artifacts
    -r, --repo <repo>             (Optional) The repository to query for deleting artifacts
    -h, --help                    Display help information
```

## 🚀 Example
To delete all artifacts for a specific repository:
```bash
gh delete-artifacts -o my-org -r my-repo
```

To delete all artifacts for all repositories in an organization:
```bash
gh delete-artifacts -o my-org
```
