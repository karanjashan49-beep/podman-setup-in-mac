# podman-setup-in-mac

- First install the brew
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew --version
```
- Then install the **podman**
```bash
brew install podman
```
- Now create and start podman 
```bash
podman machine init
podman machine start
```
- Now test podman if it works.
```bash
podman run hello-world
```
