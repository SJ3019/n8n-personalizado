FROM n8nio/n8n:latest

USER root

# Usa apk (gestor de paquetes de Alpine Linux)
RUN apk add --no-cache zip unzip ffmpeg

# Asegura permisos correctos
RUN chown -R node:node /home/node/.n8n

USER node
