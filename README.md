# PnP.PowerShell-dev-containers-demo-00

## Prerequisites

There might be two options of using Visual Studio Code development containers with PnP.PowerShell:

- Using locally installed Docker, on your desktop/laptop.
- Running containers in cloud using GitHub Codespaces (requires a paid GitHub plan)

When you run in a development container in GitHub Codespaces, you do NOT need to install any version of the PnP.PowerShell directly on your laptop/desktop.

What you will need locally is only Visual Studio Code!

### Locally Installed Docker

For using that option you need to have locally installed the following software:

- Visual Studio Code
- [Visual Studio Code extension, Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- Docker Engine. Kindly use [`Installing Docker locally` section of the `Using PnP PowerShell in Docker containers` arcticle](dev-containers.md) for installation instructions.

### GitHub Codespaces

This option requires nothing installed locally. Everything is already set up in the cloud.

## Starting working with PnP.PowerShell when you run Docker locally

1. Open the folder in Visual Studio Code.
2. Click in the bottom left corner.
3. Select `Reopen in Container`.
4. Open a new Visual Studio terminal and run `Connect-PnPOnline -Url https://<your-tenant-name>.sharepoint.com`.

The command should work even if you don't have PnP.PowerShell module installed locally on your laptop.

## Starting working with PnP.PowerShell when you run containers remotely in GitHub Codespaces

1. Open the project in GitHub site.
2. Click `Code` button.
3. Click `Create codespace on ...` button.
4. Click `Open this codespace in VS Code Desktop`.
5. Confirm opening Visual Studio Code.
6. Run `Connect-PnPOnline -Url https://<your-tenant-name>.sharepoint.com`.

The command should work even if you don't have PnP.PowerShell module installed locally on your laptop.
