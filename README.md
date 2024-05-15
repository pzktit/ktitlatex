# ktitlatex
Example of using Dev Container technology for LaTeX document preparation.

## What do you need?

1. [Visual Studio Code](https://code.visualstudio.com/) with `Remote Development` extension.
2. [Docker Engine](https://docs.docker.com/engine/install/) (only Linux) or [Docker Desktop](https://www.docker.com/products/docker-desktop/) (Linux, Windows, Mac).

## How to use it?

2. Pull the required Docker image
   ```bash
   docker pull pzktit/ktitlatex
   ```
1. Clone this repo
    ```bash
    git clone https://github.com/pzktit/ktitlatex
    ```
3. Open resulting folder in _Visual Studio Code_ DevContainer.
1. Open `Terminal`. `Problems` tab reports messages from extensions that analyze your document. The `Output` tab reports output from executed tools. Please select it and in `Tasks` choose `Latex Compiler`.
4. Build the attached sample document (play icon on the top bar).
5. `Reopen Folder Locally`: icon on left down corner with `Dev Container` name.
6. Copy folders `.devcontainer/` and `.vscode/` to the folder with your document and repeat the above steps.
1. You can select default compilation mode in `.vscode/settings.json`.
7. Study the documentation of the _Latex Workshop_, _LTeX_ and other extensions to take full advantage of using _Visual Studio Code_.

## Interested? Want more?

Please visit [ktitlatex-devcontainer](https://pzktit.github.io/ktitlatex-devcontainer/) to learn how the used DevContainer was prepared and how to prepare your own.
