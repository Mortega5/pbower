# Usage:
```bash
  pbower [<command>] [<options>]   Install versions of the components in the correct folder
```

## Commands:

    install                 Install a package locally
## Options:

    --save                  Save as bower dependencie
## Example:
  ```bash
    bower install  googletimeline-plus#v0.9-stable
  ```
  Package can be a file with multiple components

  ```
    bower install versions.txt
  ``` 
  versions.txt
  ```txt
  googletimeline-plus#v0.9-stable
  googletimeline-plus#v0.9-structural
  googletimeline-plus#v0.9-complexity
  ```
## IMPORTANT:
    The version of the component must be v{version_number}-{branch}. For example v0.9-stable