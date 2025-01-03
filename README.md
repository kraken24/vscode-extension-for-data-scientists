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
| Row A          | Link A             | Description A |
| Row B          | Link B             | Description B |
| Row C          | Link C             | Description C |
