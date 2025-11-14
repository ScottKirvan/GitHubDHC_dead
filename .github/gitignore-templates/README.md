# .gitignore Templates

This folder contains example `.gitignore` files for common project types. Copy the appropriate file(s) to your project root as `.gitignore` or merge the relevant sections into your existing `.gitignore`.

## Available Templates

- **`unreal-engine.gitignore`** - For Unreal Engine projects (UE4/UE5)
- **`python.gitignore`** - For Python projects
- **`node.gitignore`** - For Node.js/JavaScript projects
- **`cpp.gitignore`** - For C++ projects
- **`unity.gitignore`** - For Unity game projects
- **`general.gitignore`** - General OS and IDE files (useful to combine with others)

## Usage

### Replace your .gitignore
```bash
cp .github/gitignore-templates/unreal-engine.gitignore .gitignore
```

### Append to existing .gitignore
```bash
cat .github/gitignore-templates/general.gitignore >> .gitignore
```

### Combine multiple templates
```bash
cat .github/gitignore-templates/general.gitignore .github/gitignore-templates/python.gitignore > .gitignore
```
