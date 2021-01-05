# $ whoami Presentation Slides, presented by Arisa Fukuzaki

## Install Marp CLI locally

Install `@marp-team/marp-cli` in your Node projects.

```
$ yarn add --dev @marp-team/marp-cli
```

## Server mode (`--server` / `-s`)

Require to pass `--server` (`-s`) option and a directory to serve (`./slides`).

A default server port is 8080.

 `-p` stands for `--preview` option.

```
$ marp -p --server ./slides
```

More details are in Marp Github repo 👉 [https://github.com/marp-team/marp-cli/](https://github.com/marp-team/marp-cli/)