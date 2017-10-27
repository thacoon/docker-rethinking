## Overview

This installs the package needed for doing the exercises from the book "Statistical Rethinking" by Richard McElreath.

## Quickstart
`$ docker run -d -p 8787:8787 thacoon/docker-rethinking`

Visit `localhost:8787` in your browser and log in with username:password as `rstudio:rstudio`.

### Name your coontainer
`$ docker run -d -p 8787:8787 --name CHOOSE_A_NAME thacoon/docker-rethinking`

### Link a local volume to container

`$ docker run -d -p 8787:8787 -v LOCAL_PATH:/home/rstudio thacoon/docker-rethinking`

### Use custom password

`$ docker run -d -p 8787:8787 -e PASSWORD=yourpasswordhere thacoon/docker-rethinking`
