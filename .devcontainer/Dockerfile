ARG BASE_IMAGE="mcr.microsoft.com/devcontainers/python:1-3.12-bookworm"
FROM ${BASE_IMAGE}

WORKDIR /workspace

COPY ../requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt
