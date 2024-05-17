# ktitlatex
Example of using Dev Container technology for LaTeX document preparation.

## What do you need?

1. [Visual Studio Code](https://code.visualstudio.com/) with `Remote Development` extension.
2. [Docker Engine](https://docs.docker.com/engine/install/) (only Linux) or [Docker Desktop](https://www.docker.com/products/docker-desktop/) (Linux, Windows, Mac).

## How to use it?

2. Pull the required Docker image
   ```bash
   docker pull docker.io/pzktit/ktitlatex
   ```
1. Clone this repo
    ```bash
    git clone https://github.com/pzktit/ktitlatex
    ```
1. Open the resulting folder in **Visual Studio Code** DevContainer.
2. Open `Terminal`. `Problems` tab reports messages from extensions that analyze your document. The `Output` tab reports output from executed tools. Please select it and in `Tasks` choose `Latex Compiler`.
3. Build the attached sample document (play icon on the top bar).
4. `Reopen Folder Locally`: icon on left down corner with `Dev Container` name.
5. Copy folders `.devcontainer/` and `.vscode/` to the folder with your document and repeat the above steps.
6. You can select default compilation mode (`pdflatex`,`lualatex`,`xelatex`) in `.vscode/settings.json`.

## What is inside?

1. _TeXLive_ distribution distributed as Docker image `docker.io/texlive/texlive`,
2. _Code Server_ for communication with the container (you can think of a container as a remote system and _Code Server_ as alternative to _Secure Shell_),
3. Preinstalled _Visual Studio Code_ extensions:
   
   - _LaTeX Workshop_. This is a workhorse of the environment. Please read its documentation. It is worth it. It has features that provide speedup of LaTeX constructs entering, provides automatization of compilation process and permits preview with bidirectional source to PDF synchronization.
   - _LTeX_. This is autonomous/local multilanguage grammar and spell checker. It understands most of the _LaTeX_ syntax, so the number of false positive detections is relatively low.
   - _Numbered Bookmarks_ simplify navigation in large documents.
   - _Luna Paint_ permits basic operations on raster graphics, so in most cases there is no need to leave _Visual Studio Code_ environment. 

## Interested? Want more?

Please visit [ktitlatex-devcontainer](https://pzktit.github.io/ktitlatex-devcontainer/) to learn how the `ktitlatex` DevContainer was prepared and how to prepare your own.
