# DE-CLI-Tool: A Python-based CLI tool, for U-NEXT DE members

## Prequsites
- Python 3.10 or higher
- `pip install -r requirements.txt`

## Package Compilation
- `pyinstaller --onefile --clean --name de-cli-tool main.py`
- Release the compiled package in the `dist` directory to the GitHub release page: https://github.com/u-next/de-cli-tool/releases
- Update the `brew` formula with the new version and SHA256 hash: https://github.com/u-next/homebrew-de-tools/blob/main/de-cli-tool.rb

## Installation/Update
```
brew tap u-next/de-tools
brew install de-cli-tool
```