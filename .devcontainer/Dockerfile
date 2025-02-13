FROM mcr.microsoft.com/devcontainers/universal:latest

# Assicurarsi di lavorare come utente codespace
USER codespace

# Copiare i font direttamente nel sistema
COPY fonts /home/codespace/.local/share/fonts/
RUN fc-cache -fv

