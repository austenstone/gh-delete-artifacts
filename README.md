# gh-delete-artifacts

Delete all GitHub Actions artifacts for a repository or an entire organization.

## 📦 Install
```bash
gh extension install <your-github-username>/gh-delete-artifacts
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

## ⚠️ Warning
This script will permanently delete artifacts. Please use it with caution.