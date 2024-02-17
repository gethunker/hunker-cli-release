# hunker-cli
A CLI For Hunker

```bash
Installation
pip install https://github.com/gethunker/hunker-cli-release/releases/download/v0.10.0/hunker-0.10.0-py3-none-any.whl
```

```bash
Usage: hunker repo [OPTIONS] COMMAND [ARGS]...    

Options
--version                     Show the version.
--install-completion          Install completion for the current shell.  
--show-completion             Show completion for the current shell, to copy it or customize the installation.   
--help                        Show this message and exit.    

Commands
 repo                         Hunker Repo CLI    
 project                      Hunker Project CLI   
```

Example:
```bash
hunker repo upload \
    --path ./your/repo/ \
    --org-code your-org-code \
    --repo-code your-repo-code \
    --bucket-name bucket-name-here
```

```bash
hunker repo create \
   	--project-code associated-project-code \
   	--repo-code new-repo-code \
   	--repo-name new-repo-name \
   	--endpoint endpoint-name-here
```

```bash
	hunker project create \
   	--org-code associated-org-code \
   	--project-code new-project-code \
   	--project-name new-project-name \
   	--endpoint endpoint-name-here
```
