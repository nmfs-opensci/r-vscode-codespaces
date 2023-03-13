# r-vscode-codespaces
Try out running R code in a blank codespace where VScode is configured for use with R.

## How to use this repository with codespaces

Two ways:

1. Click "Use this template" and "Open in a codespace" to directly use the repository in a codespace. This options works
if you don't plan on saving any files.
2. Click "Use this template" and "Create a new repository" to make your own repository based on r-vscode-codespaces. Then, 
[open a codespace for the new repostory](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository).

There are several codespace options here:
- r-quarto (default): Use a codespace with basic R and quarto set up.
- r-base: Use a codespace with basic R set up.

See [creating a codespace in a repository](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository) for instructions on how to select which codespace you would like to use. In short, the "New with Options" button should be selected to specify which codespace configuration to use.
## I already have an R project that I want to use with codespaces!!! What should I do?

See [codespaces4r](https://github.com/nmfs-fish-tools/codespaces4r) for a utility to set this up. Another option is to directly copy over the devcontainer.json of choice into a folder named `.devcontainer` within your R project's repository.
