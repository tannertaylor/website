FROM ghcr.io/tannertaylor/devcontainer:v1.0.9
RUN sudo pacman --noconfirm -S hugo
ENTRYPOINT [ "hugo", "--source", "src", "serve", "--bind", "0.0.0.0" ]
