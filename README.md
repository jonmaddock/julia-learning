# julia-learning

Notes on learning the Julia language.

## Activating a Julia environment

- Run `julia`
- `]` then `activate .` activates an environment for the current directory
- `]` then `add <name-of-package-1>, <name-of-package-2>` installs packages
- Alternatively, `instantiate` installs all packages in a `Project.toml` file
- `] status` shows packages installed in the current active environment

`] activate` activates the default environment (equivalent to deactivating). `] activate .` activates the previously created environment in the current directory.

### Julia notebooks in VS Code

Set the notebook's "Jupyter kernel" to the Julia installation (not "Julia release channel"). This should then use the Julia environment currently activated in VS Code: the VS Code and notebook environments should be the same.