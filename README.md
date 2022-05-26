## Clone this repository

```sh
git clone --recursive git@github.com:ramirezcgn/tp-dacs-2022.git
```

### download submodules at once (without clone recursive)

```sh
git submodule update --init --recursive
```

### pull all changes in the repo including changes in the submodules

```sh
git pull --recurse-submodules
```

### pull all changes for the submodules

```sh
git submodule update --remote
```

## Run in docker

```sh
docker-compose up --build
```
