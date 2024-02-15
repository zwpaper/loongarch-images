FROM --platform=linux/loongarch64 ghcr.io/loongarchlinux/archlinux:latest

RUN pacman -Sy --noconfirm && \
    pacman -S rust --noconfirm && \
    pacman -Scc --noconfirm

WORKDIR /src

ENTRYPOINT ["cargo"]
