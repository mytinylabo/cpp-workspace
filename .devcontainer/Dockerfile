FROM gcc:latest

RUN apt-get update && apt-get install -y gdb cppcheck \
    && apt-get autoremove -y \
    && apt-get clean -y \
    && rm -rf /var/lib/apt/lists/*

LABEL Name=cppenv
