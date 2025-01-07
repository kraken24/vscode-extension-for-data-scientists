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

I have not included the basic extensions like python, pylance, jupyter notebook etc (in the list above) which are essential for python projects and need to be installed for the projects anyway.

To setup your personal AI code assistant using Continue in 10 minutes, follow the detailed tutorial [here](https://github.com/kraken24/smartypy).

Let me know if you also use some other extensions which I missed and might be good to have here.
