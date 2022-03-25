# Introduction

- [Setup workspace (Windows)](#setup-workspace--windows-)
    + [Chocolatey](#chocolatey)
    + [pyenv-win](#pyenv-win)
    + [Poetry](#poetry)

# Setup workspace (Windows)

### Chocolatey

Reference: https://chocolatey.org/install#individual

 * Run Powershell as Administrator
 * `Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))`

### pyenv-win

 * choco install pyenv-win

### Poetry

https://python-poetry.org/docs/
 * `(Invoke-WebRequest -Uri https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py -UseBasicParsing).Content | python -`
 * `poetry config virtualenvs.in-project true`
