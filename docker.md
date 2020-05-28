## Basics

`docker build (-t name) [path]` creates a docker image (optionally tagged as
`name`) from the specified `path`.

`docker run (--gpus id) [-d/-it] [image] (args)` runs a docker container from
`image` as either headless (`-d`) or an interactive shell (`-it`). Optionally,
GPUs can be allocated to the container with `--gpus` where `id` specifies the
device name (or amount) of the GPUs to be allocated (often `all`).

`docker image ls` show all docker images.

`docker image prune` removes all dangling images (ie layers that have no
relationship to any tagged images).

`docker container ls (-all)` show running (and stopped with `all`) containers.

`docker container prune` delete stopped containers.
