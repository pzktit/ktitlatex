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
4. Build the attached sample document (play icon on the top bar).
5. Close the remote connection (icon on down left corner).
6. Copy folders `.devconatiner/` and `.vscode/` to the folder with your document and repeat the above steps.
7. Study the documentation of the _Latex Workshop_, _LTeX_ and other extensions to take full advantage of using _Visual Studio Code_.

## Want more?

Please visit [ktitlatex-devcontainer](https://pzktit.github.io/ktitlatex-devcontainer/) to learn how the used DevContainer was prepared and how to prepare your own.
