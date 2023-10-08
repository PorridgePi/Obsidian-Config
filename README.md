# Obsidian Configuration
## Usage
### New Vault
1. Create a new directory: `mkdir new-vault/`
2. Change directory: `cd new-vault`
3. Initialise a new git repository: `git init`
4. Add this repository as a submodule: `git submodule add https://github.com/PorridgePi/Obsidian-Config.git .obsidian`
5. Commit changes: `git commit -m 'config: feat: add config as submodule'`
6. Open the directory in Obsidian

```sh
git init
git submodule add https://github.com/PorridgePi/Obsidian-Config.git .obsidian
git commit -m 'config: feat: add config as submodule'
```

### Updating configuration
1. Change directory: `cd new-vault`
2. Change directory to `.obsidian`: `cd .obsidian`
3. Pull changes: `git pull`
4. Change directory: `git cd ..`
5. Add changes: `git add .obsidian`
6. Commit changes: `git commit -m 'config: chore: update config'`

```sh
cd .obsidian
git pull
cd ..
git add .obsidian
git commit -m 'config: chore: update config'
```
