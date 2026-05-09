FROM ubuntu:22.04

# 日本語が化けないようにフォントと、画面を映すための道具（noVNC）を最初から入れる設定です
RUN apt update && apt install -y \
    bash sudo vim git curl build-essential \
    fonts-noto-cjk \
    fluxbox novnc python3-websockify x11vnc \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace
