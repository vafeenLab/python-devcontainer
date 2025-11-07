FROM python:3.11-slim

# Настройка локали и окружения
ENV DEBIAN_FRONTEND=noninteractive
ENV LANG=C.UTF-8

# Установка полезных утилит (опционально, но рекомендуется)
RUN apt-get update && apt-get install -y \
    git \
    curl \
    && rm -rf /var/lib/apt/lists/*

# Рабочая директория
WORKDIR /workspace