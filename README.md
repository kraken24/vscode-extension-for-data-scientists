# VS Code Extensions for Data Scientists

This repository contains a list of VS Code Extensions that help improve productivity, code readability and documentation of your data science projects

## Installing extentions from a text file

```bash
cat extensions_list.txt | xargs -n 1 code --install-extension
```

## Exporting extentions to a file

```bash
code --list-extensions > extensions_list.txt
```

To save the extensions with their respective version:
```bash
code --list-extensions --show-versions > extensions_list.txt
```

## Essential VS Code Extensions for Data Scientists

| Extension Name | Marketplace Link | Purpose |
| -------------- | ------------------ | ------- |
| Auto Doc Strings | [https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring) | **Generate docstrings automatically.** |
| Autopep8 | [https://marketplace.visualstudio.com/items?itemName=ms-python.autopep8](https://marketplace.visualstudio.com/items?itemName=ms-python.autopep8) | **Format Python code to conform to PEP 8 standards.** |
| Preview | [https://marketplace.visualstudio.com/items?itemName=searking.preview-vscode](https://marketplace.visualstudio.com/items?itemName=searking.preview-vscode) | **Preview Markdown files within VS Code.** |
| Prettier - Code Formatter | [https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) | **Automatically format code for improved readability and consistency.** |
| CodeSnap | [https://marketplace.visualstudio.com/items?itemName=robertz.code-snapshot](https://marketplace.visualstudio.com/items?itemName=robertz.code-snapshot) | **Capture code snippets as images with syntax highlighting.** |
| Live Server | [https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) | **Launch a local development server with live reloading for web development.** |
| Better Comments | [https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) | **Improve code readability with categorized and color-coded comments.** |
| Path Intellisense | [https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) | **Autocomplete file paths for faster coding.** |
| Rest Client | [https://marketplace.visualstudio.com/items?itemName=humao.rest-client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) | **Test APIs directly within VS Code.** |
| VS Code Icons | [https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons) | **Enhance visual clarity with file-specific icons.** |
| Continue AI Code Assistant | [https://marketplace.visualstudio.com/items?itemName=continue.continue](https://marketplace.visualstudio.com/items?itemName=continue.continue) | **AI-powered code completion and assistance.** |
| ESLint | [https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) | **Identify and fix JavaScript code errors and enforce coding style.** |



| Extension Name | Marketplace Link | Purpose |
|---|---|---|
| Auto Doc Strings | Generate docstrings automatically. | [https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring) |
| Autopep8 | Format Python code to conform to PEP 8 standards. | [https://marketplace.visualstudio.com/items?itemName=ms-python.autopep8](https://marketplace.visualstudio.com/items?itemName=ms-python.autopep8) |
| Preview | Preview Markdown files within VS Code. | [https://marketplace.visualstudio.com/items?itemName=searking.preview-vscode](https://marketplace.visualstudio.com/items?itemName=searking.preview-vscode) |
| Prettier - Code Formatter | Automatically format code for improved readability and consistency. | [https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) |
| CodeSnap | Capture code snippets as images with syntax highlighting. | [https://marketplace.visualstudio.com/items?itemName=robertz.code-snapshot](https://marketplace.visualstudio.com/items?itemName=robertz.code-snapshot) |
| Live Server | Launch a local development server with live reloading for web development. | [https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) |
| Better Comments | Improve code readability with categorized and color-coded comments. | [https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) |
| Path Intellisense | Autocomplete file paths for faster coding. | [https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) |
| Rest Client | Test APIs directly within VS Code. | [https://marketplace.visualstudio.com/items?itemName=humao.rest-client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) |
| VS Code Icons | Enhance visual clarity with file-specific icons. | [https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons) |
| Continue AI Code Assistant | AI-powered code completion and assistance. | [https://marketplace.visualstudio.com/items?itemName=continue.continue](https://marketplace.visualstudio.com/items?itemName=continue.continue) |
| ESLint | Identify and fix JavaScript code errors and enforce coding style. | [https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) |

I have not included the basic extensions like python, pylance, jupyter notebook etc (in the list above) which are essential for python projects but they are listed in the `extensions_list.txt` file.

To setup your personal AI code assistant using Continue in 10 minutes, follow the detailed tutorial [here](https://github.com/kraken24/smartypy).

Let me know if you also use some other extensions which I missed and might be good to have here.
