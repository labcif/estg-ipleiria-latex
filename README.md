# Latex template for MCIF thesis - ESTG - IPLeiria

This template can be used for a thesis written in the degree MCIF of ESTG IPLeiria.

To download to your computer click "Code > Download zip"

## Devcontainer

This template comes with a [devcontainer](https://code.visualstudio.com/docs/devcontainers/containers) allowing compilation of the document in vscode without having to install all the necessary tools by hand. The devcontainer will automatically create a docker container to run the Latex compilation tools, and works either in Windows or Linux. The container will have a Tex Live installation and the [vscode latex extension](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) should be used for working in the document. 

To use the devcontainer:

1. [Install docker](https://docs.docker.com/engine/install/)
2. [Install vscode](https://code.visualstudio.com/download)
3. Open this directory in vscode
4. Click on the green square in the left bottom corner of the vscode window and select "Reopen in container". This will create a docker container with TexLive installed. This has to be done only once but might take 1h to complete.

## Installing dependencies without using docker

1. Install Tex Live full
2. Install python Pygments package: `pip install Pygments`

## Compiling with makefile

```
make pdf
```

## Compiling with vscode

Use "Build LaTeX project" from the Latex workshop menu
