FROM mcr.microsoft.com/devcontainers/python:3.11

# Upgrade pip and install Python tools
RUN pip install --no-cache-dir --upgrade pip

# Preinstall dependencies
COPY requirements.txt /tmp/requirements.txt
RUN pip install --no-cache-dir -r /tmp/requirements.txt
