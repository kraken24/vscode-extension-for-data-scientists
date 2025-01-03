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
| Auto Doc Strings | [https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring) | Write docstrings |
| Pep8 | [https://marketplace.visualstudio.com/items?itemName=ms-python.autopep8](https://marketplace.visualstudio.com/items?itemName=ms-python.autopep8) | Pep8 compliance |
| Debug Python | [https://marketplace.visualstudio.com/items?itemName=ms-python.debugpy](https://marketplace.visualstudio.com/items?itemName=ms-python.debugpy) | Python requirement |
| Python | [https://marketplace.visualstudio.com/items?itemName=ms-python.python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) | Python requirement |
| Pylance | [https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance) | Python requirement |
| Jupyter Notebook | [https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) | Jupyter Notebook requirement |
| Jupyter Notebook Keymap | [https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter-keymap](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter-keymap) | Jupyter Notebook requirement |
| Jupyter Notebook Renderers | [https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter-renderers](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter-renderers) | Jupyter Notebook requirement |
| Jupyter Notebook Cell-tags | [https://marketplace.visualstudio.com/items?itemName=ms-toolsai.vscode-jupyter-cell-tags](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.vscode-jupyter-cell-tags) | Jupyter Notebook requirement |
| Jupyter Notebook Slideshow | [https://marketplace.visualstudio.com/items?itemName=ms-toolsai.vscode-jupyter-slideshow](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.vscode-jupyter-slideshow) | Jupyter Notebook requirement |
| Preview Markdown | [https://marketplace.visualstudio.com/items?itemName=searking.preview-vscode](https://marketplace.visualstudio.com/items?itemName=searking.preview-vscode) | To preview markdown files |
| Continue AI Code Assistant | [https://marketplace.visualstudio.com/items?itemName=continue.continue](https://marketplace.visualstudio.com/items?itemName=continue.continue) | AI code assistant |
| Prettier - Code Formatter | [https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) | Auto format your code with best practices and common sense in mind |
| CodeSnap | [https://marketplace.visualstudio.com/items?itemName=robertz.code-snapshot](https://marketplace.visualstudio.com/items?itemName=robertz.code-snapshot) | Take beautiful screenshots of your code with 1-click, syntax highlighting included |
| Live Server | [https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) | Launches a development local Server with live reload feature for static & dynamic pages |
| Better Comments | [https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) | Helps in increasing the readability of your comments present in the code, you can categorize and color code your comments based upon the type of the comments so that they are more visible and readable |
| ESLint | [https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) | Catch errors and enforce coding standards with ESLint |
| Path Intellisense | [https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) | Autocompletes file paths as you type |
| Rest Client | [https://marketplace.visualstudio.com/items?itemName=humao.rest-client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) | To test APIs directly from VSCode without the need of any external tools like Postman |
| VS Code Icons | [https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons) | Easier to differentiate between file types by adding file-specific icons in your editor |
