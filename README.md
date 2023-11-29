# hunker-cli
A CLI For Hunker

```bash
Installation
pip install https://github.com/gethunker/hunker-cli-release/releases/download/v0.0.00/hunker-0.0.0-py3-none-any.whl
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
 upload                       Archive and upload a .git repository path to an existing repository.            
```

Example:
```bash
hunker repo upload \
    --path ./your/repo/ \
    --org-code your-org-code \
    --project-code your-project-code \
    --repo-code your-repo-code \
    --bucket-name repo-bucket-1234567890-us-east-1
```
