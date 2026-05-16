# Environment Setup

## Requirements

- GitHub Desktop is installed and provides a bundled Git executable.
- The repository is cloned at:
  `C:\BaiduSyncdisk\codex\Personal Website\github-site\jinxu-xj.github.io`
- The GitHub Pages site publishes from the `master` branch.
- Ruby/Jekyll local preview is optional; no local Jekyll build was confirmed during memory initialization.

## Git

Use GitHub Desktop bundled Git if `git` is not on PATH:

```powershell
& "$env:LOCALAPPDATA\GitHubDesktop\app-3.5.8\resources\app\git\cmd\git.exe" status -sb
```

Common workflow:

```powershell
& "$env:LOCALAPPDATA\GitHubDesktop\app-3.5.8\resources\app\git\cmd\git.exe" status -sb
& "$env:LOCALAPPDATA\GitHubDesktop\app-3.5.8\resources\app\git\cmd\git.exe" add <paths>
& "$env:LOCALAPPDATA\GitHubDesktop\app-3.5.8\resources\app\git\cmd\git.exe" commit -m "Update academic homepage"
& "$env:LOCALAPPDATA\GitHubDesktop\app-3.5.8\resources\app\git\cmd\git.exe" push origin master
```

Fetch before pushing if remote changes appear:

```powershell
& "$env:LOCALAPPDATA\GitHubDesktop\app-3.5.8\resources\app\git\cmd\git.exe" fetch origin
& "$env:LOCALAPPDATA\GitHubDesktop\app-3.5.8\resources\app\git\cmd\git.exe" status -sb
```

## Local Preview

If Ruby and Bundler are installed:

```powershell
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open:

```text
http://localhost:4000
```

If Ruby/Jekyll is not available, verify pushed content through GitHub Pages after deployment:

```powershell
Invoke-WebRequest -Uri 'https://jinxu-xj.github.io/' -UseBasicParsing
```

## Deployment

Deployment happens through GitHub Pages after pushing to `master`.

Current live site:

```text
https://jinxu-xj.github.io/
```

## Environment Variables

No project-specific environment variables are currently required.

Do not commit secrets or private CV/referee information.
