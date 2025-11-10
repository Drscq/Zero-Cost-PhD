# Generate requirements.txt Automatically

## Using pip freeze
```bash
# After installing packages in your activated venv
pip freeze > requirements.txt
```

This captures all installed packages and their versions.

## Install from requirements.txt
```bash
pip install -r requirements.txt
```

## Using pipreqs (cleaner, direct dependencies only)
```bash
# Install pipreqs
pip install pipreqs

# Generate requirements.txt
pipreqs . --force
```
