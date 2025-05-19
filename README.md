## Self-Hostable WebLaTeX

This repository is a Docker-based, self-hostable fork of [sanjib-sen/WebLaTeX](https://github.com/sanjib-sen/WebLaTeX), customized for local and private deployment, where you do not need any codespaces.

### Requirements

- Docker installed: https://docs.docker.com/engine/install/
- Visual Studio Code with [Dev Containers Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

---

### Steps to Launch Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/lepotatoguy/weblatex-self-hosted.git
   cd weblatex-self-hosted

2. Open in Visual Studio Code and Reopen in Container.

3. The environment will be built using the local .devcontainer/Dockerfile. (Wait for the container to build; initial build takes time)

Then go to [demo.tex](./demo.tex) to get started.

To collaborate with your friends on the single LaTeX project, you will find an option below the window of VS Code called "Live Share". Click on that and you will get a prompt to share the link which you can use. 